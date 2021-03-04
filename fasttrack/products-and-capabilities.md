---
title: 제품 및 기능
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 2/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: 이 항목에는 FastTrack에서 지원하는 작업 시나리오 및 시작하기 전에 필요한 원본 환경 기대치에 대한 세부 정보가 포함되어 있습니다. 현재 설정에 따라 성공적인 온보드를 위한 최소 요구 사항까지 원본 환경을 개선하는 재구성 계획을 세우기 위해 함께 작업합니다.
ms.openlocfilehash: 05936adee3f21e6078933a686dfa8dc24c33d1be
ms.sourcegitcommit: cf630a48697177b9cce6c0fbc67a7e7a0b752167
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/03/2021
ms.locfileid: "50416567"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="161ac-104">제품 및 기능</span><span class="sxs-lookup"><span data-stu-id="161ac-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="161ac-105">FastTrack에서 지원하는 서비스 및 시나리오</span><span class="sxs-lookup"><span data-stu-id="161ac-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="161ac-106">이 항목에는 FastTrack에서 지원하는 작업 시나리오 및 시작하기 전에 필요한 원본 환경 기대치에 대한 세부 정보가 포함되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="161ac-107">현재 설정에 따라 성공적인 온보드를 위한 최소 요구 사항까지 원본 환경을 개선하는 재구성 계획을 세우기 위해 함께 작업합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="161ac-108">FastTrack은 핵심 기능(모든 사용자에 대해 공통)을 먼저 Microsoft Online Services 다음 각 적합한 서비스를 온보더링하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="161ac-109">일반</span><span class="sxs-lookup"><span data-stu-id="161ac-109">General</span></span>](#general)
  - [<span data-ttu-id="161ac-110">보안 및 규정 준수</span><span class="sxs-lookup"><span data-stu-id="161ac-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="161ac-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="161ac-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="161ac-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="161ac-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="161ac-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="161ac-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="161ac-114">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="161ac-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="161ac-115">App Assure</span><span class="sxs-lookup"><span data-stu-id="161ac-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="161ac-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="161ac-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="161ac-117">Office 365 미국 정부에 대한 원본 환경 기대치에 대한 정보는 [Office 365 미국 정부에 대한 원본 환경 기대치](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="161ac-118">일반 사항</span><span class="sxs-lookup"><span data-stu-id="161ac-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="161ac-119"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="161ac-120"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="161ac-121"><strong>원본 환경 기대치</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="161ac-122"><strong>핵심 온보딩</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="161ac-123">서비스 프로비전, 테넌트 및 ID 통합과 관련된 핵심 온보드에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="161ac-124">또한 보안, 네트워크 연결 및 규정 준수에 대한 토론을 포함하여 Exchange Online, SharePoint Online 및 Microsoft Teams와 같은 온보더링 서비스를 위한 토대를 제공하기 위한 단계도 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">포함되어 있습니다.</a></span><span class="sxs-lookup"><span data-stu-id="161ac-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="161ac-125">하나 이상의 적합한 서비스에 대한 온보딩은 핵심 온보딩이 완료되면 시작됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="161ac-126"></li>
</ul>  

<strong> ID 통합 </strong></span><span class="sxs-lookup"><span data-stu-id="161ac-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="161ac-127">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="161ac-128">Azure AD Connect(단일 포리스트 또는 다중 포리스트) 설치 및 구성 및 라이선스(그룹 기반 라이선싱 포함)를 포함하여 Azure AD(Azure Active Directory)에 대한 동기화를 위해 사내 Active Directory ID 준비</span><span class="sxs-lookup"><span data-stu-id="161ac-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="161ac-129">그룹 기반 라이선싱 사용을 포함하여 대량 가져오기 및 라이선싱을 비롯한 클라우드 ID 만들기</span><span class="sxs-lookup"><span data-stu-id="161ac-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="161ac-130">클라우드 여정, 암호 해시 동기화, 통과 인증 또는 AD FS(Active Directory Federation Services)에 대한 올바른 인증 방법을 선택하고 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="161ac-131">Azure AD Connect 도구와 동기화된 단일 Active Directory 포리스트 및 ID를 사용하는 고객에 대해 AD FS를 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-131">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="161ac-132">이렇게 하려면 Windows Server 2012 R2 Active Directory Federation Services 2.0 이상이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-132">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="161ac-133">암호 해시 동기화 또는 통과 인증을 사용하여 AD FS에서 Azure AD로 인증 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="161ac-133">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="161ac-134">SSO(Single Sign-On)를 위해 사전 통합된 앱(예: Azure AD 갤러리 SaaS(Software-as-a-Service) 앱)을 AD FS에서 Azure AD로 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="161ac-134">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="161ac-135">Azure AD 갤러리에서 SaaS 앱과 SSO를 통합할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-135">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="161ac-136">앱 통합 자습서 목록에 나열된 사전 통합된 SaaS 앱에 대해 자동 사용자 프로비저닝을 사용하도록 설정(Azure AD 갤러리 SaaS 앱 및 아웃바운드 프로비전에만 제한) <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list"></a></span><span class="sxs-lookup"><span data-stu-id="161ac-136">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="161ac-137"><strong>네트워크 사용 설정 </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="161ac-137"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="161ac-138">FastTrack 혜택의 일부로 Microsoft 365의 최고 수준의 성능을 보장하기 위해 클라우드 서비스에 연결하는 모범 사례를 활용하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-138">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="161ac-139"><strong>Active Directory 포리스트</strong> 이러한 포리스트 수준은 다음 포리스트 구성을 통해 Windows Server 2003 이상으로 설정됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-139"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-140">단일 Active Directory 포리스트.</span><span class="sxs-lookup"><span data-stu-id="161ac-140">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="161ac-141">단일 Active Directory 계정 포리스트 및 리소스 포리스트(Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype) 토폴로지</span><span class="sxs-lookup"><span data-stu-id="161ac-141">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="161ac-142">여러 개의 Active Directory 계정 포리스트 및 리소스 포리스트(Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype) 토폴로지</span><span class="sxs-lookup"><span data-stu-id="161ac-142">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="161ac-143">포리스트 중 하나가 Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype가 있는 중앙 집중식 Active Directory 계정 포리스트인 여러 Active Directory 계정 포리스트</span><span class="sxs-lookup"><span data-stu-id="161ac-143">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="161ac-144">각각이 자체 Exchange 조직을 갖는 다중 Active Directory 계정 포리스트</span><span class="sxs-lookup"><span data-stu-id="161ac-144">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="161ac-145">필요한 경우 테넌트 구성 및 Azure Active Directory와의 통합에 필요한 작업입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-145">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="161ac-146">
  <strong>중요</strong>  </span><span class="sxs-lookup"><span data-stu-id="161ac-146">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="161ac-147">다중 포리스트 Active Directory 시나리오의 경우 Lync 2010, Lync 2013 또는 비즈니스용 Skype가 배포된 경우 Exchange와 동일한 Active Directory 포리스트에 배포해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-147">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="161ac-148">Exchange 다중 하이브리드 구성에서 여러 Exchange 조직과 함께 여러 Active Directory 포리스트를 구현하는 경우 원본 포리스트 간의 공유 UPN(사용자 계정 이름) 네임스페이스는 지원되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-148">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="161ac-149">Exchange 조직 간의 기본 SMTP 네임스페이스도 구분해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-149">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="161ac-150">자세한 내용은 여러 <a href="https://go.microsoft.com/fwlink/?linkid=845444">Active Directory 포리스트가 있는 하이브리드 배포를 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="161ac-150">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="161ac-151">모든 다중 포리스트 구성의 경우 AD FS(Active Directory Federation Services) 배포의 범위를 벗어날 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-151">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="161ac-152">이에 대한 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">지원은 Microsoft 파트너에게</a> 문의하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-152">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="161ac-153"><strong>Microsoft 365 앱</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-153"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="161ac-154">다음에 대한 원격 배포 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-154">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-155">배포 문제 해결</span><span class="sxs-lookup"><span data-stu-id="161ac-155">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="161ac-156">Microsoft 365 관리 센터 및 Windows PowerShell을 사용하여 최종 사용자 및 디바이스 기반 라이선스 할당</span><span class="sxs-lookup"><span data-stu-id="161ac-156">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="161ac-157">간편 실행을 사용하여 Office 365 포털에서 Microsoft 365 앱 설치</span><span class="sxs-lookup"><span data-stu-id="161ac-157">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="161ac-158">iOS 또는 Android 장치에 Office Mobile 앱(에: Outlook Mobile, Word Mobile, Excel Mobile 및 PowerPoint Mobile) 설치</span><span class="sxs-lookup"><span data-stu-id="161ac-158">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="161ac-159">Office 365 배포 도구를 사용하여 업데이트 설정 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-159">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="161ac-160">로컬 또는 클라우드 설치의 선택 및 설치</span><span class="sxs-lookup"><span data-stu-id="161ac-160">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="161ac-161">배포 패티지를 구성하기 위해 Office 사용자 지정 도구 또는 네이티브 XML을 사용하여 Office 배포 도구 구성 XML 작성</span><span class="sxs-lookup"><span data-stu-id="161ac-161">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="161ac-162">Microsoft Endpoint Configuration Manager를 사용하여 배포(Endpoint Configuration Manager 패키지 생성에 대한 지원 포함)</span><span class="sxs-lookup"><span data-stu-id="161ac-162">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="161ac-163">또한 이전 버전의 Office와 함께 작동한 매크로나 추가 기능의 경우 호환성 문제가 있는 경우 App Assure 프로그램을 통해 추가 비용 없는 호환성 문제를 수정하기 위한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-163">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="161ac-164">자세한 내용은 Windows <a href="#windows-10">10의</a> <strong>App Assure</strong> 부분을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-164">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="161ac-165">온라인 클라이언트 소프트웨어는 Microsoft 365 및 Office의 시스템 요구 사항에 정의된 최소 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">수준 이상이 되어야 합니다.</a></span><span class="sxs-lookup"><span data-stu-id="161ac-165">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="161ac-166"><strong>네트워크 상태</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-166"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="161ac-167">조직의 사이트가 네트워크 연결의 Microsoft의 원칙에 얼마나 부합하는지 보여주는 환경에서 주요 네트워크 연결 데이터를 획득하고 해석하는 원격 지침을 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">제공합니다.</a></span><span class="sxs-lookup"><span data-stu-id="161ac-167">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="161ac-168">그러면 마이그레이션 속도, 사용자 환경, 서비스 성능 및 안정성에 직접적인 영향을 미치는 네트워크 점수가 강조 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-168">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="161ac-169">또한 이 데이터로 강조 표시된 모든 수정 단계를 안내하여 네트워크 점수를 개선하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-169">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="161ac-170">Microsoft 365 관리 센터 액세스.</span><span class="sxs-lookup"><span data-stu-id="161ac-170">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="161ac-171">최신 버전의 Microsoft 365 앱이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-171">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="161ac-172"><a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365</a>관리 센터(미리 보기)의 네트워크 성능 권장 사항에 따라 활성화된 위치 서비스.</span><span class="sxs-lookup"><span data-stu-id="161ac-172">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="161ac-173">보안 및 규정 준수</span><span class="sxs-lookup"><span data-stu-id="161ac-173">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="161ac-174"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-174"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="161ac-175"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-175"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="161ac-176"><strong>원본 환경 기대치</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-176"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="161ac-177"><strong>Azure AD(Azure Active Directory) 및 Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-177"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="161ac-178">다음 시나리오에 대한 클라우드 ID 보안에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-178">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="161ac-179">

<strong>보안 기본 인프라</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="161ac-179">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="161ac-180">Azure MFA(다단계 인증)(클라우드 전용), Microsoft Authenticator 앱 및 Azure MFA 및 SSPR(셀프 서비스 암호 재설정)에 대한 결합 등록을 포함하여 ID에 대해 강력한 인증을 구성하고 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-180">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="161ac-181">Azure AD Premium이 아닌 고객의 경우 보안 기본값을 사용하여 ID를 보호하는 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-181">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="161ac-182">Azure AD 프리미엄 고객의 경우 조건부 액세스를 사용하여 ID를 보호하는 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-182">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="161ac-183">Azure AD 암호 보호를 사용하여 취약한 암호의 사용을 감지하고 차단합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-183">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="161ac-184">Azure AD 응용 프로그램 프록시를 사용하여 사내 웹앱에 대한 원격 액세스 보안</span><span class="sxs-lookup"><span data-stu-id="161ac-184">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="161ac-185">Azure Identity Protection을 사용하여 위험 기반 감지 및 수정을 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-185">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="161ac-186">사용자 지정 브랜드가 있는 로고, 텍스트 및 이미지를 포함하여 사용자 지정 로그인 화면 사용</span><span class="sxs-lookup"><span data-stu-id="161ac-186">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="161ac-187">Azure AD B2B를 사용하여 게스트 사용자와 앱 및 서비스를 안전하게 공유합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-187">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="161ac-188">RBAC(역할 기반 액세스 제어) 기본 제공 관리 역할을 사용하여 Office 365 관리자에 대한 액세스를 관리하고 권한 있는 관리자 계정 수를 줄입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-188">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="161ac-189">하이브리드 Azure AD 조인 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-189">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="161ac-190">Azure AD 조인 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-190">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="161ac-191">
  
<strong>모니터링 및 보고</strong>  
</span><span class="sxs-lookup"><span data-stu-id="161ac-191">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="161ac-192">Azure AD Connect Health를 사용하여 AD FS, Azure AD Connect 및 도메인 컨트롤러에 대한 원격 모니터링을 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-192">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="161ac-193">
  
<strong>거버넌스</strong>  
</span><span class="sxs-lookup"><span data-stu-id="161ac-193">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="161ac-194">Azure AD 권리 권한 관리를 사용하여 Azure AD ID 및 액세스 수명 주기를 대규모로 관리합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-194">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="161ac-195">Azure AD 액세스 검토를 사용하여 Azure AD 그룹 구성원 자격, 엔터프라이즈 앱 액세스 및 역할 할당 관리</span><span class="sxs-lookup"><span data-stu-id="161ac-195">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-196">Azure AD 사용 약관 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-196">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-197">Azure AD Privileged Identity Management를 사용하여 권한 있는 관리자 계정에 대한 액세스 관리 및 제어</span><span class="sxs-lookup"><span data-stu-id="161ac-197">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="161ac-198">
  
<strong>자동화 및 효율성 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="161ac-198">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="161ac-199">Azure AD SSPR 사용.</span><span class="sxs-lookup"><span data-stu-id="161ac-199">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="161ac-200">사용자가 Azure AD 셀프 서비스 그룹 관리를 사용하여 자체 클라우드 보안 또는 Office 365 그룹을 만들고 관리할 수 있도록 허용합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-200">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="161ac-201">Azure AD 위임된 그룹 관리를 사용하여 엔터프라이즈 앱에 대한 위임된 액세스 관리</span><span class="sxs-lookup"><span data-stu-id="161ac-201">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="161ac-202">Azure AD 동적 그룹을 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-202">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="161ac-203">컬렉션을 사용하여 내 앱 포털에서 앱 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-203">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="161ac-204">Azure AD 및 Azure AD Premium 기능과의 통합을 방지하는 식별된 문제 수정을 포함하여 Azure AD Premium에 대한 준비를 하여, 해당 환경은 Azure AD Premium에 대해 준비되었습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-204">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="161ac-205"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="161ac-205"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="161ac-206">Azure Information Protection에 대한 자세한 내용은 이 표의 <strong>Microsoft Information Protection을</strong> 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-206">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="161ac-207"><strong>검색 & 응답</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-207"><strong>Discovery & Response</strong></span></span></td>
<td>  

<span data-ttu-id="161ac-208"><strong>Advanced eDiscovery</strong>
  
</span><span class="sxs-lookup"><span data-stu-id="161ac-208"><strong>Advanced eDiscovery</strong>
  
</span></span><ul>
<li>  <span data-ttu-id="161ac-209">안전한 링크, 안전한 첨부 파일 및 피싱 방지 사용.</span><span class="sxs-lookup"><span data-stu-id="161ac-209">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="161ac-210">자동화, 조사 및 대응 구성.</span><span class="sxs-lookup"><span data-stu-id="161ac-210">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="161ac-211">공격 시뮬레이터 사용.</span><span class="sxs-lookup"><span data-stu-id="161ac-211">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="161ac-212">보고 및 위협 분석.</span><span class="sxs-lookup"><span data-stu-id="161ac-212">Reporting and threat analytics.</span></span>  </li>
</ul>

<span data-ttu-id="161ac-213"><strong>고급</strong> 감사(E5에서만 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-213"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="161ac-214">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-214">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="161ac-215">고급 감사를 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-215">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="161ac-216">검색 감사 로그 UI 및 기본 감사 PowerShell 명령 수행</span><span class="sxs-lookup"><span data-stu-id="161ac-216">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="161ac-217">

<strong> 준수 관리자</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-217">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="161ac-218">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-218">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="161ac-219">역할 유형 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-219">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="161ac-220">평가 추가 및 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-220">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="161ac-221">개선 작업을 구현하고 준수 점수에 어떤 영향을 미치는지 확인하여 준수를 평가합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-221">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="161ac-222">기본 제공 컨트롤 매핑 및 컨트롤 평가 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-222">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="161ac-223">평가 내에서 보고서 생성</span><span class="sxs-lookup"><span data-stu-id="161ac-223">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="161ac-224">

<strong>다음은 범위를 벗어날 수 있는 예제입니다. </strong> 
</span><span class="sxs-lookup"><span data-stu-id="161ac-224">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="161ac-225">사용자 지정 스크립팅 또는 코딩.</span><span class="sxs-lookup"><span data-stu-id="161ac-225">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="161ac-226">eDiscovery API.</span><span class="sxs-lookup"><span data-stu-id="161ac-226">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="161ac-227">데이터 커넥터.</span><span class="sxs-lookup"><span data-stu-id="161ac-227">Data connectors.</span></span> </li>
<li> <span data-ttu-id="161ac-228">규정 준수 경계 및 보안 필터.</span><span class="sxs-lookup"><span data-stu-id="161ac-228">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="161ac-229">데이터 조사.</span><span class="sxs-lookup"><span data-stu-id="161ac-229">Data investigations.</span></span></li>
<li> <span data-ttu-id="161ac-230">데이터 주체 요청.</span><span class="sxs-lookup"><span data-stu-id="161ac-230">Data subject requests.</span></span></li>
<li> <span data-ttu-id="161ac-231">디자인, 설계 및 타사 문서 검토.</span><span class="sxs-lookup"><span data-stu-id="161ac-231">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="161ac-232">산업 및 지역 규정 및 요구 사항을 준수합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-232">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="161ac-233">준수 관리자의 평가에 대한 권장 개선 작업의 실무를 구현합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-233">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="161ac-234">일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 최소 시스템 요구 사항은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-234">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="161ac-235"><strong>Insider Threat Management</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-235"><strong>Insider Threat Management</strong></span></span></td>

<td>  <span data-ttu-id="161ac-236">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-236">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="161ac-237">정책 만들기 및 설정 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-237">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="161ac-238">보고서 및 경고 액세스</span><span class="sxs-lookup"><span data-stu-id="161ac-238">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="161ac-239">사례 생성.</span><span class="sxs-lookup"><span data-stu-id="161ac-239">Creating cases.</span></span></li>
<li> <span data-ttu-id="161ac-240">알림 서식 파일 만들기</span><span class="sxs-lookup"><span data-stu-id="161ac-240">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="161ac-241">HR(인적 자원) 커넥터를 만드는 방법에 대한 지침입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-241">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="161ac-242">

<strong> 통신 규정 준수 </strong></span><span class="sxs-lookup"><span data-stu-id="161ac-242">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="161ac-243">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-243">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="161ac-244">정책 만들기 및 설정 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="161ac-245">보고서 및 경고 액세스</span><span class="sxs-lookup"><span data-stu-id="161ac-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="161ac-246">알림 서식 파일 만들기</span><span class="sxs-lookup"><span data-stu-id="161ac-246">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="161ac-247">

<strong> 준수 관리자</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-247">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="161ac-248">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-248">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="161ac-249">역할 유형 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-249">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="161ac-250">평가 추가 및 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-250">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="161ac-251">개선 작업을 구현하고 준수 점수에 어떤 영향을 미치는지 확인하여 준수를 평가합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-251">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="161ac-252">기본 제공 컨트롤 매핑 및 컨트롤 평가 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-252">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="161ac-253">평가 내에서 보고서 생성</span><span class="sxs-lookup"><span data-stu-id="161ac-253">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="161ac-254">

<strong>다음은 범위를 벗어날 수 있는 예제입니다. </strong> 
</span><span class="sxs-lookup"><span data-stu-id="161ac-254">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="161ac-255">Power Automate 흐름 만들기 및 관리</span><span class="sxs-lookup"><span data-stu-id="161ac-255">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="161ac-256">데이터 커넥터(HR 커넥터 이상).</span><span class="sxs-lookup"><span data-stu-id="161ac-256">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="161ac-257">사용자 지정 정규식(RegEx) 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-257">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="161ac-258">디자인, 설계 및 타사 문서 검토.</span><span class="sxs-lookup"><span data-stu-id="161ac-258">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="161ac-259">정보 장벽.</span><span class="sxs-lookup"><span data-stu-id="161ac-259">Information barriers.</span></span></li>
<li> <span data-ttu-id="161ac-260">권한이 부여된 액세스 관리.</span><span class="sxs-lookup"><span data-stu-id="161ac-260">Privileged access management.</span></span></li>
<li> <span data-ttu-id="161ac-261">산업 및 지역 규정 및 요구 사항을 준수합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-261">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="161ac-262">준수 관리자의 평가에 대한 권장 개선 작업의 실무를 구현합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-262">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="161ac-263">일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 최소 시스템 요구 사항은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-263">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="161ac-264"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-264"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="161ac-265">Microsoft 365 Defender는 엔드포인트, ID, 전자 메일 및 앱 전반에 걸쳐 감지, 예방, 조사 및 대응을 조정하여 정교한 공격으로부터 통합된 보호를 제공하는 통합 사전 및 사후 침해 엔터프라이즈 방어 제품군입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-265">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="161ac-266">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-266">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="161ac-267">Microsoft 365 보안 센터의 개요를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-267">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="161ac-268">전체 공격 범위, 영향을 미치는 자산 및 함께 그룹화되는 자동화된 수정 조치를 보장하여 중요한 작업에 중점을 두는 것을 포함하여 제품 간 인시던트 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-268">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="161ac-269">Microsoft 365 Defender가 자동 자동 복구를 통해 손상될 수 있는 자산, 사용자, 장치 및 사서함에 대한 조사를 오케스트레이션하는 방법을 시연합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-269">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="161ac-270">고객이 여러 데이터 집합에서 전자 메일, 데이터, 장치 및 계정에 영향을 주는 침입 시도 및 위반 활동을 사전적으로 헌팅하는 방법에 대한 설명 및 예제를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-270">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="161ac-271">고객에게 Microsoft 보안 점수를 사용하여 전체적으로 보안 자세를 검토하고 개선할 수 있는 방법을 보여 넣습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-271">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="161ac-272"><strong>다음은 범위를 벗어날 수 있는 예제입니다.</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-272"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="161ac-273">고객의 수정 활동에 대한 프로젝트 관리.</span><span class="sxs-lookup"><span data-stu-id="161ac-273">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="161ac-274">지속적인 관리, 위협 대응 및 수정</span><span class="sxs-lookup"><span data-stu-id="161ac-274">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="161ac-275">배포 지침 또는 교육:</span><span class="sxs-lookup"><span data-stu-id="161ac-275">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="161ac-276">다양한 경고 유형 및 모니터링된 활동을 수정하거나 해석하는 방법</span><span class="sxs-lookup"><span data-stu-id="161ac-276">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="161ac-277">사용자, 컴퓨터, 측면 이동 경로 또는 엔터티를 조사하는 방법</span><span class="sxs-lookup"><span data-stu-id="161ac-277">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="161ac-278">사용자 지정 위협 헌팅.</span><span class="sxs-lookup"><span data-stu-id="161ac-278">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="161ac-279">SIEM(보안 정보 및 이벤트 관리) 또는 API 통합</span><span class="sxs-lookup"><span data-stu-id="161ac-279">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="161ac-280"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-280"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="161ac-281">Microsoft Cloud App Security는 모든 Microsoft 및 타사 클라우드 서비스에서 사이버 위협을 식별하고 퇴치하기 위한 풍부한 가시성, 데이터 이동 제어 및 정교한 분석을 제공하는 CASB(Cloud Access Security Broker)입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-281">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="161ac-282">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-282">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-283">다음을 비롯한 포털 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-283">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="161ac-284">사용자 그룹 가져오기.</span><span class="sxs-lookup"><span data-stu-id="161ac-284">Importing user groups.</span></span></li>
<li> <span data-ttu-id="161ac-285">관리자 액세스 및 설정 관리</span><span class="sxs-lookup"><span data-stu-id="161ac-285">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="161ac-286">배포를 지정하여 모니터링하거나 모니터링에서 제외할 특정 사용자 그룹을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-286">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="161ac-287">IP 범위 및 태그 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-287">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="161ac-288">로고 및 사용자 지정 메시징을 사용하여 최종 사용자 환경을 개인 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-288">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="161ac-289">클라우드 검색을 설정하여 섀도 IT를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-289">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="161ac-290">끝점용 Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="161ac-290">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="161ac-291">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="161ac-291">Zscaler.</span></span></li>
<li> <span data-ttu-id="161ac-292">iboss.</span><span class="sxs-lookup"><span data-stu-id="161ac-292">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="161ac-293">앱 <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">커넥터를 사용하여</a> 주요 앱을 연결합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-293">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="161ac-294">조건부 액세스 및 Cloud App Security 포털에서 조건부 액세스 앱 컨트롤을 설정하여 실시간 세션 컨트롤을 적용합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-294">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="161ac-295">Cloud App Security 및 클라우드 검색 대시보드 배포</span><span class="sxs-lookup"><span data-stu-id="161ac-295">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="161ac-296">조직의 우선 순위에 따라 앱 위험 점수를 사용자 지정합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-296">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="161ac-297">앱 태그 및 범주 만들기</span><span class="sxs-lookup"><span data-stu-id="161ac-297">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="161ac-298">앱의 제재 및 비인가.</span><span class="sxs-lookup"><span data-stu-id="161ac-298">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="161ac-299">활동 및 파일 로그 사용.</span><span class="sxs-lookup"><span data-stu-id="161ac-299">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="161ac-300">OAuth 앱 관리</span><span class="sxs-lookup"><span data-stu-id="161ac-300">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="161ac-301">Microsoft 365 Defender 포털의 인시던트 상관 관계 이해</span><span class="sxs-lookup"><span data-stu-id="161ac-301">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="161ac-302">CASB에 대한 상위 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20개</a> 사용 사례(다음을 제외한 최대 6개의 정책 생성 또는 업데이트 포함)에 대한 구성 지원을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-302">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="161ac-303">IaaS(인터넷 as a Service) 환경의 구성 감사(#18).</span><span class="sxs-lookup"><span data-stu-id="161ac-303">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="161ac-304">IaaS 환경의 위협으로부터 보호하기 위한 사용자 활동 모니터링(#19).</span><span class="sxs-lookup"><span data-stu-id="161ac-304">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="161ac-305"><strong>다음은 범위를 벗어날 수 있는 예제입니다.</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-305"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="161ac-306">고객의 수정 활동에 대한 프로젝트 관리.</span><span class="sxs-lookup"><span data-stu-id="161ac-306">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="161ac-307">지속적인 관리, 위협 대응 및 수정</span><span class="sxs-lookup"><span data-stu-id="161ac-307">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="161ac-308">Docker 또는 로그 수집기를 사용하여 연속 보고서에 대한 자동 로그 업로드 인프라, 설치 또는 배포 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-308">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="161ac-309">자세한 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">내용은 CASB의 상위 20개 사용</a> 사례를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-309">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="161ac-310">클라우드 검색 스냅숏 보고서 만들기</span><span class="sxs-lookup"><span data-stu-id="161ac-310">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="161ac-311">블록 스크립트를 사용하여 앱 사용을 차단합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-311">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="161ac-312">사용자 지정 앱 연결.</span><span class="sxs-lookup"><span data-stu-id="161ac-312">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="161ac-313">타사 ISP(ID 공급자) 및 DLP(데이터 손실 방지) 공급자와 통합</span><span class="sxs-lookup"><span data-stu-id="161ac-313">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="161ac-314">고급 헌팅에 대한 교육 또는 지침.</span><span class="sxs-lookup"><span data-stu-id="161ac-314">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="161ac-315">Microsoft Power Automate 플레이북을 포함한 자동화된 조사 및 수정</span><span class="sxs-lookup"><span data-stu-id="161ac-315">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="161ac-316">SIEM(보안 정보 및 이벤트 관리) 또는 API 통합(Azure Sentinel 포함)</span><span class="sxs-lookup"><span data-stu-id="161ac-316">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="161ac-317">개념 증명으로 Cloud App Discovery 배포</span><span class="sxs-lookup"><span data-stu-id="161ac-317">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="161ac-318"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-318"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="161ac-319">Microsoft Defender Advanced Threat Protection (ATP)는 엔터프라이즈 네트워크가 고급 위협을 방지, 탐지, 조사 및 대응하는 데 도움이 되도록 설계된 플랫폼입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-319">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="161ac-320">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-320">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-321">끝점을 보호하는 기술을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-321">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="161ac-322">끝점 보호 및 장치 제한 프로필 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-322">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="161ac-323">OS 버전 및 장치 관리(Intune, Microsoft Endpoint Configuration Manager, GOS(그룹 정책 개체) 및 타사 구성 포함) 및 Windows Defender AV 서비스 또는 기타 끝점 보안 소프트웨어의 상태를 평가합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-323">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="161ac-324">Windows AV 서비스 또는 기타 끝점 보안 소프트웨어의 상태 평가</span><span class="sxs-lookup"><span data-stu-id="161ac-324">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="161ac-325">네트워크 트래픽을 제한하는 Proxies 및 방화벽 평가</span><span class="sxs-lookup"><span data-stu-id="161ac-325">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="161ac-326">온보딩 끝점을 사용하여 ATP 에이전트 프로필을 배포하는 방법을 설명하여 Microsoft Defender ATP 서비스를 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-326">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="161ac-327">다음에 대한 배포 지침, 구성 지원 및 교육:</span><span class="sxs-lookup"><span data-stu-id="161ac-327">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="161ac-328">위협 및 취약성 관리.</span><span class="sxs-lookup"><span data-stu-id="161ac-328">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-329">공격 표면 감소.</span><span class="sxs-lookup"><span data-stu-id="161ac-329">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-330">차세대 보호.</span><span class="sxs-lookup"><span data-stu-id="161ac-330">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-331">끝점 감지 및 대응.</span><span class="sxs-lookup"><span data-stu-id="161ac-331">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-332">자동화된 조사 및 조치.</span><span class="sxs-lookup"><span data-stu-id="161ac-332">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-333">보안 점수.</span><span class="sxs-lookup"><span data-stu-id="161ac-333">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="161ac-334">시뮬레이션 및 자습서 검토(예: 연습 시나리오, 가짜 맬웨어 및 자동화된 조사)</span><span class="sxs-lookup"><span data-stu-id="161ac-334">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="161ac-335">보고 및 위협 분석 기능 개요.</span><span class="sxs-lookup"><span data-stu-id="161ac-335">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="161ac-336">Office 365 ATP와 Microsoft Defender ATP 통합.</span><span class="sxs-lookup"><span data-stu-id="161ac-336">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="161ac-337">Microsoft Defender 보안 센터 포털 탐색.</span><span class="sxs-lookup"><span data-stu-id="161ac-337">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="161ac-338">다음 운영 체제는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-338">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="161ac-339">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="161ac-339">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-340">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="161ac-340">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-341">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="161ac-341">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-342">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="161ac-342">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-343">Windows Server Semi-Annual 채널(SAC) 버전 1803.</span><span class="sxs-lookup"><span data-stu-id="161ac-343">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-344">macOS 버전 10.13, 10.14 및 10.15.</span><span class="sxs-lookup"><span data-stu-id="161ac-344">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="161ac-345">
<strong>참고:</strong> 모든 Windows Server 버전은 최신 버전의 System Center Configuration Manager 2012(버전 1012 R2, 1511 또는 1602) 또는 Microsoft Endpoint Configuration Manager(버전 2002 이상)에서 관리해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-345">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="161ac-346"></li>
</ul>

<strong>다음은 범위를 벗어날 수 있는 예제입니다. </strong>  
</span><span class="sxs-lookup"><span data-stu-id="161ac-346"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="161ac-347">고객의 수정 활동에 대한 프로젝트 관리.</span><span class="sxs-lookup"><span data-stu-id="161ac-347">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="161ac-348">현장 지원.</span><span class="sxs-lookup"><span data-stu-id="161ac-348">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="161ac-349">지속적인 관리와 위협 대응.</span><span class="sxs-lookup"><span data-stu-id="161ac-349">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="161ac-350">다음 Microsoft Defender ATP 에이전트에 대한 온보딩 또는 구성:</span><span class="sxs-lookup"><span data-stu-id="161ac-350">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="161ac-351">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="161ac-351">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-352">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="161ac-352">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-353">Linux.</span><span class="sxs-lookup"><span data-stu-id="161ac-353">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-354">모바일 장치(Android 및 iOS).</span><span class="sxs-lookup"><span data-stu-id="161ac-354">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="161ac-355">VDI(가상 데스크톱 인프라)(영구적 또는 비영구적)</span><span class="sxs-lookup"><span data-stu-id="161ac-355">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="161ac-356">서버 온보드 및 구성:</span><span class="sxs-lookup"><span data-stu-id="161ac-356">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="161ac-357">오프라인 통신을 위한 프록시 서버 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-357">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-358">다운 수준 Configuration Manager 인스턴스 및 버전에서 Configuration Manager 배포 패키지 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-358">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-359">Azure 보안 센터에 서버 온보드</span><span class="sxs-lookup"><span data-stu-id="161ac-359">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-360">Configuration Manager에서 관리하지 않는 서버입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-360">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="161ac-361">macOS 온보더링 및 구성:</span><span class="sxs-lookup"><span data-stu-id="161ac-361">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="161ac-362">수동 Intune 기반 배포.</span><span class="sxs-lookup"><span data-stu-id="161ac-362">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-363">JAMF 기반 배포.</span><span class="sxs-lookup"><span data-stu-id="161ac-363">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="161ac-364">기타 MDM(모바일 장치 관리) 제품 기반 배포.</span><span class="sxs-lookup"><span data-stu-id="161ac-364">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-365">수동 배포.</span><span class="sxs-lookup"><span data-stu-id="161ac-365">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="161ac-366">다음 공격 표면 감소에 대한 기능:</span><span class="sxs-lookup"><span data-stu-id="161ac-366">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="161ac-367">하드웨어 기반 격리.</span><span class="sxs-lookup"><span data-stu-id="161ac-367">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-368">앱 컨트롤.</span><span class="sxs-lookup"><span data-stu-id="161ac-368">App control.</span></span>  
  </li>
<li> <span data-ttu-id="161ac-369">장치 제어.</span><span class="sxs-lookup"><span data-stu-id="161ac-369">Device control.</span></span></li>
<li>  
  <span data-ttu-id="161ac-370">악용 방지.</span><span class="sxs-lookup"><span data-stu-id="161ac-370">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-371">네트워크 방화벽.</span><span class="sxs-lookup"><span data-stu-id="161ac-371">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="161ac-372">계정 보호 기능의 구성 또는 관리는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-372">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="161ac-373">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="161ac-373">Windows Hello</span></span></li>
<li> <span data-ttu-id="161ac-374">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="161ac-374">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="161ac-375">BitLocker의 구성 또는 관리.</span><span class="sxs-lookup"><span data-stu-id="161ac-375">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="161ac-376">Microsoft 위협 전문가 등록 또는 구성.</span><span class="sxs-lookup"><span data-stu-id="161ac-376">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="161ac-377">API 또는 SIEM(보안 정보 및 이벤트 관리) 연결을 검토하는 구성 또는 교육</span><span class="sxs-lookup"><span data-stu-id="161ac-377">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="161ac-378">MTP(Microsoft 위협 방지) 등록 또는 구성.</span><span class="sxs-lookup"><span data-stu-id="161ac-378">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="161ac-379">고급 헌팅에 대한 교육 또는 지침.</span><span class="sxs-lookup"><span data-stu-id="161ac-379">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="161ac-380">Kusto 쿼리의 사용 또는 생성에 대한 교육 또는 지침입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-380">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="161ac-381">Microsoft <a href="https://go.microsoft.com/fwlink/?linkid=2080150">파트너에게 문의하여</a> 이러한 서비스에 대한 지원을 요청하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-381">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="161ac-382"><strong>Id용 Microsoft Defender </strong></span><span class="sxs-lookup"><span data-stu-id="161ac-382"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="161ac-383">ID용 Microsoft Defender는 온-프레미스 Active Directory 신호를 활용하여 조직에서 일어나는 고급 위협, ID 손상 및 악의적인 내부자 작업을 식별, 감지 및 조사하는 클라우드 기반 보안 솔루션입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-383">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="161ac-384">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-384">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="161ac-385">ID에 대한 Defender 인스턴스 만들기.</span><span class="sxs-lookup"><span data-stu-id="161ac-385">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="161ac-386">ID에 대한 Defender를 Active Directory에 연결합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-386">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="161ac-387">다음을 포함하여 도메인 컨트롤러에 ID용 Defender 센서를 배포하기 위한 환경의 준비 상태를 평가합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-387">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="161ac-388">자원 용량 계획을 위한 크기 조정 도구 실행</span><span class="sxs-lookup"><span data-stu-id="161ac-388">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="161ac-389">감사 도구를 실행하여 센서와 도메인 컨트롤러의 호환성을 평가합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-389">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="161ac-390">다음을 포함하여 도메인 컨트롤러에서 직접 네트워크 트래픽 및 Windows 이벤트를 캡처하고 구문 분석하기 위해 센서를 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-390">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="161ac-391">센서 패키지 다운로드.</span><span class="sxs-lookup"><span data-stu-id="161ac-391">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="161ac-392">센서 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-392">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="161ac-393">도메인 컨트롤러에 센서를 자동으로 설치합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-393">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="161ac-394">다중 포리스트 환경에 센서 배포</span><span class="sxs-lookup"><span data-stu-id="161ac-394">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="161ac-395">ID용 Defender를 Microsoft Cloud App Security와 통합합니다(Cloud App Security 라이선스가 필요하지 않습니다).</span><span class="sxs-lookup"><span data-stu-id="161ac-395">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="161ac-396">다음에 대한 배포 지침, 구성 지원 및 교육 제공</span><span class="sxs-lookup"><span data-stu-id="161ac-396">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="161ac-397">환경을 조정하여 "노이즈"를 줄입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-397">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="161ac-398">ID 보안 환경 평가 보고서 이해</span><span class="sxs-lookup"><span data-stu-id="161ac-398">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="161ac-399">사용자 조사 우선 순위 점수 및 사용자 조사 순위 보고서 이해</span><span class="sxs-lookup"><span data-stu-id="161ac-399">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="161ac-400">비활성 사용자 보고서 이해</span><span class="sxs-lookup"><span data-stu-id="161ac-400">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="161ac-401">손상된 계정에 대한 수정 옵션 제공</span><span class="sxs-lookup"><span data-stu-id="161ac-401">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="161ac-402">ATA(Advanced Threat Analytics)에서 ID용 Defender로의 마이그레이션을 촉진합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-402">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="161ac-403"><strong>다음은 범위를 벗어날 수 있는 예제입니다.</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-403"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="161ac-404">고객의 수정 활동에 대한 프로젝트 관리.</span><span class="sxs-lookup"><span data-stu-id="161ac-404">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="161ac-405">지속적인 관리, 위협 대응 및 수정</span><span class="sxs-lookup"><span data-stu-id="161ac-405">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="161ac-406">다음을 포함하여 ID용 Defender 센서 배포</span><span class="sxs-lookup"><span data-stu-id="161ac-406">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="161ac-407">수동 용량 계획</span><span class="sxs-lookup"><span data-stu-id="161ac-407">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="161ac-408">독립 실행형 용량으로 센서 배포</span><span class="sxs-lookup"><span data-stu-id="161ac-408">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="161ac-409">NIC(Network Interface Card) 팀 어댑터를 사용하여 센서 배포</span><span class="sxs-lookup"><span data-stu-id="161ac-409">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="161ac-410">타사 도구를 통해 센서 배포</span><span class="sxs-lookup"><span data-stu-id="161ac-410">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="161ac-411">웹 프록시 연결을 통해 ID용 Defender 클라우드 서비스에 연결합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-411">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="161ac-412">허니토ken 만들기 및 관리.</span><span class="sxs-lookup"><span data-stu-id="161ac-412">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="161ac-413">배포 지침 또는 교육:</span><span class="sxs-lookup"><span data-stu-id="161ac-413">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="161ac-414">다양한 경고 유형 및 모니터링된 활동을 수정하거나 해석합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-414">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="161ac-415">사용자, 컴퓨터, 측면 이동 경로 또는 엔터티 조사</span><span class="sxs-lookup"><span data-stu-id="161ac-415">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="161ac-416">위협 또는 고급 헌팅.</span><span class="sxs-lookup"><span data-stu-id="161ac-416">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="161ac-417">인시던트 대응.</span><span class="sxs-lookup"><span data-stu-id="161ac-417">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="161ac-418">Id용 Defender에 대한 보안 경고 랩 자습서 제공</span><span class="sxs-lookup"><span data-stu-id="161ac-418">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="161ac-419">ID에 대한 Defender가 지명된 센서를 통해 syslog 서버에 보안 경고를 전송하여 의심스러운 활동을 감지할 때 알림을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-419">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="161ac-420">SAMR(보안 계정 관리자 원격) 프로토콜을 사용하여 쿼리를 수행하여 특정 컴퓨터의 로컬 관리자를 식별하도록 ID에 대한 Defender를 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-420">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="161ac-421">VPN 연결의 정보를 사용자 프로필 페이지에 추가하도록 VPN 솔루션을 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-421">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="161ac-422">SIEM(보안 정보 및 이벤트 관리) 또는 API 통합(Azure Sentinel 포함)</span><span class="sxs-lookup"><span data-stu-id="161ac-422">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="161ac-423">개념 증명으로 ID 센서용 Defender 배포</span><span class="sxs-lookup"><span data-stu-id="161ac-423">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="161ac-424">Active Directory가 배포되었습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-424">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="161ac-425">ID 센서용 Defender를 설치하려는 도메인 컨트롤러는 ID용 Defender 클라우드 서비스에 인터넷에 연결되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-425">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="161ac-426">ID 클라우드 서비스용 Defender와 통신하려면 방화벽 및 프록시가 열려 있어야 합니다(\*.atp.azure.com 포트 443이 열려 있어야 합니다).</span><span class="sxs-lookup"><span data-stu-id="161ac-426">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="161ac-427">다음 중 하나에서 실행되는 도메인 컨트롤러</span><span class="sxs-lookup"><span data-stu-id="161ac-427">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="161ac-428">Windows Server 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="161ac-428">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="161ac-429">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="161ac-429">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="161ac-430">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="161ac-430">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="161ac-431">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="161ac-431">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="161ac-432">KB4487044(OS 빌드 17763.316)가 있는 Windows Server 2019</span><span class="sxs-lookup"><span data-stu-id="161ac-432">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><span data-ttu-id="161ac-433"><strong>Microsoft 정보 거버넌스</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-433"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="161ac-434">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-434">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-435">보존 레이블 및 정책 만들기 및 게시(E5에서만 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-435">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="161ac-436">레코드 관리(E5에서만 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-436">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="161ac-437">파일 계획 만들기 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-437">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="161ac-438">레코드 만들기 및 관리(이벤트 기반 레코드 포함)</span><span class="sxs-lookup"><span data-stu-id="161ac-438">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="161ac-439">검토.</span><span class="sxs-lookup"><span data-stu-id="161ac-439">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="161ac-440">

<strong> 준수 관리자</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-440">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="161ac-441">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-441">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="161ac-442">역할 유형 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-442">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="161ac-443">평가 추가 및 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-443">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="161ac-444">개선 작업을 구현하고 준수 점수에 어떤 영향을 미치는지 확인하여 준수를 평가합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-444">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="161ac-445">기본 제공 컨트롤 매핑 및 컨트롤 평가 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-445">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="161ac-446">평가 내에서 보고서 생성</span><span class="sxs-lookup"><span data-stu-id="161ac-446">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="161ac-447">

  <strong>다음은 범위를 벗어날 수 있는 예제입니다. </strong>  
</span><span class="sxs-lookup"><span data-stu-id="161ac-447">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="161ac-448">레코드 관리 파일 계획 개발</span><span class="sxs-lookup"><span data-stu-id="161ac-448">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="161ac-449">데이터 커넥터.</span><span class="sxs-lookup"><span data-stu-id="161ac-449">Data connectors.</span></span></li>
<li> <span data-ttu-id="161ac-450">SharePoint의 정보 아키텍처 개발.</span><span class="sxs-lookup"><span data-stu-id="161ac-450">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="161ac-451">사용자 지정 스크립팅 및 코딩.</span><span class="sxs-lookup"><span data-stu-id="161ac-451">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="161ac-452">디자인, 설계 및 타사 문서 검토.</span><span class="sxs-lookup"><span data-stu-id="161ac-452">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="161ac-453">E3에 대한 지원.</span><span class="sxs-lookup"><span data-stu-id="161ac-453">Support for E3.</span></span></li>
<li> <span data-ttu-id="161ac-454">산업 및 지역 규정 및 요구 사항을 준수합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-454">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="161ac-455">준수 관리자의 평가에 대한 권장 개선 작업의 실무를 구현합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-455">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="161ac-456">일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 최소 시스템 요구 사항은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-456">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="161ac-457"><strong>Microsoft Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-457"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="161ac-458">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-458">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-459">데이터 분류(E3 및 E5에서 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-459">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="161ac-460">중요한 정보 유형(E3 및 E5에서 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-460">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="161ac-461">민감도 레이블 만들기(E3 및 E5에서 지원).</span><span class="sxs-lookup"><span data-stu-id="161ac-461">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="161ac-462">민감도 레이블 적용(E3 및 E5에서 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-462">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="161ac-463">교육 가능한 분류자(E5에서 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-463">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="161ac-464">콘텐츠 탐색기 및 활동 탐색기를 사용하여 데이터를 알 수 있습니다(E5에서 지원).</span><span class="sxs-lookup"><span data-stu-id="161ac-464">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="161ac-465">정책을 사용하여 레이블 게시(수동 및 자동)(E5에서 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-465">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="161ac-466">Windows 10 장치에 대한 끝점 DLP(데이터 손실 방지) 정책 만들기(E5에서 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-466">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="161ac-467">Microsoft Teams 채팅 및 채널에 대한 DLP 정책 만들기</span><span class="sxs-lookup"><span data-stu-id="161ac-467">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="161ac-468">

<strong> 준수 관리자</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-468">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="161ac-469">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-469">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="161ac-470">역할 유형 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-470">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="161ac-471">평가 추가 및 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-471">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="161ac-472">개선 작업을 구현하고 준수 점수에 어떤 영향을 미치는지 확인하여 준수를 평가합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-472">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="161ac-473">기본 제공 컨트롤 매핑 및 컨트롤 평가 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-473">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="161ac-474">평가 내에서 보고서 생성</span><span class="sxs-lookup"><span data-stu-id="161ac-474">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="161ac-475">

<strong> Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-475">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="161ac-476">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-476">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="161ac-477">테넌트 활성화 및 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-477">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="161ac-478">레이블 및 정책 만들기 및 설정(P1 및 P2에서 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-478">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="161ac-479">문서에 정보 보호 적용(P1 및 P2에서 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-479">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="161ac-480">Windows에서 실행되고 Azure Information Protection 클라이언트(P2에서 지원)를 사용하여 Office 앱(예: Word, PowerPoint, Excel 및 Outlook)에서 정보를 자동으로 분류하고 레이블을 지정합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-480">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="161ac-481">Azure Information Protection 스캐너를 사용하여 미사용 파일 검색 및 레이블 지정(P1 및 P2에서 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-481">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="161ac-482">Exchange Online 메일 흐름 규칙을 사용하여 전송 중인 전자 메일 모니터링</span><span class="sxs-lookup"><span data-stu-id="161ac-482">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="161ac-483">Microsoft Azure RMS(권한 관리 서비스), OME(Office 365 메시지 암호화) 및 DLP(데이터 손실 방지)를 사용하여 보호를 적용하려는 경우도 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-483">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="161ac-484"><strong>다음은 범위를 벗어날 수 있는 예제입니다. </strong></span><span class="sxs-lookup"><span data-stu-id="161ac-484"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="161ac-485">고객 키.</span><span class="sxs-lookup"><span data-stu-id="161ac-485">Customer key.</span></span></li>
<li><span data-ttu-id="161ac-486">중요한 정보 유형에 대한 사용자 지정 정규식(RegEx) 개발</span><span class="sxs-lookup"><span data-stu-id="161ac-486">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="161ac-487">키워드 사전 만들기 또는 수정</span><span class="sxs-lookup"><span data-stu-id="161ac-487">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="161ac-488">사용자 지정 스크립팅 및 코딩.</span><span class="sxs-lookup"><span data-stu-id="161ac-488">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="161ac-489">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="161ac-489">Azure Purview.</span></span></li>
<li> <span data-ttu-id="161ac-490">디자인, 설계 및 타사 문서 검토.</span><span class="sxs-lookup"><span data-stu-id="161ac-490">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="161ac-491">산업 및 지역 규정 및 요구 사항을 준수합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-491">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="161ac-492">준수 관리자의 평가에 대한 권장 개선 작업의 실무를 구현합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-492">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="161ac-493">일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 Azure Information Protection을 제외하고 최소 시스템 요구 사항은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-493">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="161ac-494"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-494"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="161ac-495">고객 선행 요구 사항 책임은 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-495">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="161ac-496">검사할 파일 공유 위치 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-496">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="161ac-497">승인된 분류법</span><span class="sxs-lookup"><span data-stu-id="161ac-497">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="161ac-498">키 관리에 대한 규정 제한 또는 요구 사항을 이해합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-498">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="161ac-499">Azure AD와 동기화된 프레미스 Active Directory에 대해 만들어진 서비스 계정입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-499">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="161ac-500">분류 및 보호를 위해 구성된 레이블입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-500">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="161ac-501">Azure Information Protection 스캐너에 대한 모든 선행조치가 준비됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-501">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="161ac-502">자세한 내용은 Azure Information Protection 통합 레이블 지정 스캐너 설치 및 배포를 위한 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites를 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="161ac-502">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="161ac-503">사용자 디바이스가 지원되는 운영 체제를 실행하고 있으며 필요한 필수 필수 장치가 설치되어 있는지 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-503">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="161ac-504">자세한 내용은 다음을 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-504">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="161ac-505"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">관리자 가이드: 사용자를 위한 Azure Information Protection 통합 레이블 클라이언트 설치</a>   </span><span class="sxs-lookup"><span data-stu-id="161ac-505"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="161ac-506"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">iOS 또는 Android용 Azure Information Protection 앱은 무엇입니까?</a>  </span><span class="sxs-lookup"><span data-stu-id="161ac-506"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="161ac-507">하이브리드 지원을 위한 AD RMS(Active Directory RMS) 커넥터를 포함하여 Azure RMS 커넥터 및 서버의 설치 및 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-507">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="161ac-508">배포에 이러한 옵션 중 하나만 필요한 경우 BYOK(Bring Your Own Key), DKE(이중 키 암호화)(통합 레이블 클라이언트만 해당) 또는 Hold Your Own Key (HYOK)(클래식 클라이언트만 해당)의 설치 및 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-508">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="161ac-509"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-509"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="161ac-510">앱 및 장치에 대한 클라우드 기반 MDM(모바일 장치 관리) 및 MAM(모바일 앱 관리) 공급자로 Intune을 사용할 준비를 준비하는 방법에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-510">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="161ac-511">정확한 단계는 원본 환경에 따라 다르며 모바일 장치와 모바일 앱 관리 요구 사항에 기반합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-511">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="161ac-512">해당 단계는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-512">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-513">최종 사용자에게 라이선스 부여</span><span class="sxs-lookup"><span data-stu-id="161ac-513">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="161ac-514">Intune에서 사용할 ID를 구성하는 데는 Azure AD(클라우드 ID)를 활용합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-514">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="161ac-515">Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기</span><span class="sxs-lookup"><span data-stu-id="161ac-515">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="161ac-516">다음을 비롯한 관리 요구에 따라 MDM 기관 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-516">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-517">Intune이 유일한 MDM 솔루션인 경우 Intune을 MDM 기관으로 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-517">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="161ac-518">MDM 지침 제공:</span><span class="sxs-lookup"><span data-stu-id="161ac-518">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-519">MDM 관리 정책의 유효성을 검사하는 데 사용할 테스트 그룹 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-519">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="161ac-520">다음과 같은 MDM 관리 정책 및 서비스 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-520">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-521">웹 링크 또는 딥 링크를 통해 지원되는 각 플랫폼에 대한 앱 배포.</span><span class="sxs-lookup"><span data-stu-id="161ac-521">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="161ac-522">조건부 액세스 정책.</span><span class="sxs-lookup"><span data-stu-id="161ac-522">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="161ac-523">조직에 기존 인증 기관, 무선 네트워크 또는 VPN 인프라가 있는 경우 전자 메일, 무선 네트워크 및 VPN 프로필 배포.</span><span class="sxs-lookup"><span data-stu-id="161ac-523">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="161ac-524">Intune 데이터 웨어하우스에 연결</span><span class="sxs-lookup"><span data-stu-id="161ac-524">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="161ac-525">다음에 Intune 통합:</span><span class="sxs-lookup"><span data-stu-id="161ac-525">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-526">원격 지원을 위한 팀 뷰어(팀 뷰어 구독 필요)</span><span class="sxs-lookup"><span data-stu-id="161ac-526">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="161ac-527">MTD(Mobile Threat Defense) 파트너 솔루션(MTD 구독이 필요합니다.)</span><span class="sxs-lookup"><span data-stu-id="161ac-527">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="161ac-528">원격 비용 관리 솔루션(통신 비용 관리 솔루션 구독 필요)</span><span class="sxs-lookup"><span data-stu-id="161ac-528">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="161ac-529">각 지원되는 플랫폼의 장치를 Intune에 등록합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-529">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="161ac-530">앱 보호 지침 제공:</span><span class="sxs-lookup"><span data-stu-id="161ac-530">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-531">지원되는 각 플랫폼에 대한 Intune 앱 보호 정책 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-531">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="161ac-532">관리되는 앱에 대한 조건부 액세스 정책 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-532">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="161ac-533">앞서 언급한 MAM 정책을 통해 적절한 사용자 그룹을 대상으로 지정합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-533">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="161ac-534">관리되는 앱 사용 현황 보고서 사용.</span><span class="sxs-lookup"><span data-stu-id="161ac-534">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="161ac-535">레거시 PC 관리에서 Intune MDM으로의 마이그레이션 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-535">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="161ac-536">
 
</li>
</ul>
  
<strong>클라우드 연결</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-536">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="161ac-537">Intune을 통해 기존 Configuration Manager 환경을 클라우드에 연결하기 위한 준비를 안내합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-537">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="161ac-538">정확한 단계는 원본 환경에 따라 다릅니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-538">The exact steps depend on your source environment.</span></span> <span data-ttu-id="161ac-539">해당 단계는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-539">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="161ac-540">최종 사용자에게 라이선스 부여</span><span class="sxs-lookup"><span data-stu-id="161ac-540">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="161ac-541">온-프레미스 Active Directory 및 클라우드 ID를 활용하여 Intune에서 사용할 ID 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-541">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="161ac-542">Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기</span><span class="sxs-lookup"><span data-stu-id="161ac-542">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="161ac-543">하이브리드 Azure AD 조인을 설정하는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-543">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="161ac-544">MDM 자동 등록을 위한 Azure AD 설정에 대한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-544">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="161ac-545">원격 인터넷 기반 장치 관리의 공동 관리를 위한 솔루션으로 사용될 때 클라우드 관리 게이트웨이를 설정하는 방법에 대한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-545">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="161ac-546">Intune으로 전환할 지원되는 작업 부하를 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-546">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="161ac-547">Intune에서 등록된 디바이스에서 Configuration Manager 클라이언트를 설치합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-547">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="161ac-548"><strong>iOS 및 Android용 Outlook 모바일을 안전하게 배포</strong> 조직에서 iOS 및 Android용 Outlook 모바일을 안전하게 배포하여 사용자에게 필요한 모든 앱이 설치되도록 하는 데 도움이 되는 지침을 제공할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-548"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="161ac-549">Intune을 통해 iOS 및 Android용 Outlook 모바일을 안전하게 배포하는 단계는 원본 환경에 따라 다를 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-549">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="161ac-550">여기에는 다음이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-550">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-551">Apple App Store 또는 Google Play 스토어를 통해 iOS 및 Android용 Outlook, Microsoft Authenticator 및 Intune 회사 포털 앱을 다운로드합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-551">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="161ac-552">설정에 대한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-552">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-553">Intune을 사용하여 iOS 및 Android용 Outlook, Microsoft Authenticator 및 Intune 회사 포털 앱 배포.</span><span class="sxs-lookup"><span data-stu-id="161ac-553">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="161ac-554">앱 보호 정책.</span><span class="sxs-lookup"><span data-stu-id="161ac-554">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="161ac-555">조건부 액세스 정책.</span><span class="sxs-lookup"><span data-stu-id="161ac-555">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="161ac-556">앱 구성 정책.</span><span class="sxs-lookup"><span data-stu-id="161ac-556">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="161ac-557">IT 관리자는 Intune을 사용하여 무선 네트워크 및 VPN 프로필 배포를 계획할 때 기존 인증 기관, 무선 네트워크 및 VPN 인프라가 프로덕션 환경에서 이미 작동하고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-557">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="161ac-558"><strong>참고:</strong>FastTrack 서비스 혜택에는 Intune에 대한 인증 기관, 무선 네트워크, VPN 인프라 또는 Apple MDM 푸시 인증서를 설정하거나 구성하기 위한 지원이 포함되어서는 안 됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-558"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="161ac-559"><strong>참고</strong>: 클라우드 연결 기능을 지원하는 데 필요한 최소 요구 사항에 맞게 Configuration Manager 사이트 서버 또는 Configuration Manager 클라이언트를 설정하거나 업그레이드하기 위한 지원은 FastTrack 서비스 혜택에 포함되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-559"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="161ac-560">이에 대한 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">지원은 Microsoft 파트너에게</a> 문의하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-560">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="161ac-561"><strong>Microsoft Defender ATP(Advanced Threat Protection)에 통합된 Intune</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-561"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="161ac-562"><strong>참고:</strong>Microsoft Defender ATP와 Intune을 통합하고 Windows 10 위험 수준 평가를 기반으로 장치 준수 정책을 만드는 데 도움을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-562"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="161ac-563">구매, 라이선스 또는 정품 인증에 대한 지원은 제공하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-563">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="161ac-564">이에 대한 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">지원은 Microsoft 파트너에게</a> 문의하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-564">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="161ac-565"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-565"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="161ac-566">IT 관리자는 하드웨어 공급 업체가 사용자를 대신하여 하드웨어 ID를 업로드하거나 Windows Autopilot 서비스로 업로드하는 방법으로 조직에 장치를 등록합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-566">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>

<tr class="odd">
<td><span data-ttu-id="161ac-567"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-567"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="161ac-568">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-568">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-569">안전한 링크, 안전한 첨부 파일 및 피싱 방지 사용.</span><span class="sxs-lookup"><span data-stu-id="161ac-569">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="161ac-570">자동화, 조사 및 대응 구성.</span><span class="sxs-lookup"><span data-stu-id="161ac-570">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="161ac-571">공격 시뮬레이터 사용.</span><span class="sxs-lookup"><span data-stu-id="161ac-571">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="161ac-572">보고 및 위협 분석.</span><span class="sxs-lookup"><span data-stu-id="161ac-572">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="161ac-573">일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 최소 시스템 요구 사항은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-573">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="161ac-574">Office 365</span><span class="sxs-lookup"><span data-stu-id="161ac-574">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="161ac-575"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-575"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="161ac-576"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-576"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="161ac-577"><strong>원본 환경 기대치</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-577"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="161ac-578"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-578"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="161ac-579">Exchange Online의 경우 조직에서 전자 메일을 사용할 수 있도록 하는 프로세스를 안내합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-579">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="161ac-580">정확한 단계는 원본 환경 및 전자 메일 마이그레이션 계획에 따라 달라 집니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-580">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="161ac-581">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-581">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-582">Office 365에서 유효성이 검사된 모든 메일 사용이 가능한 도메인에 대해 EOP(Exchange Online Protection) 기능을 설정합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-582">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="161ac-583">MX(메일 교환) 레코드를 Office 365로 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-583">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="161ac-584">구독 서비스의 일부인 경우 Office 365 ATP 기능 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-584">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="161ac-585">자세한 내용은 이 표의 <strong>Office 365 Advanced Threat Protection</strong> 부분을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-585">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="161ac-p127">구독 서비스의 일부로 Office 365에서 확인된 모든 메일 사용 가능 도메인에 대한 데이터 손실 방지(DLP) 기능 설정. MX 레코드가 Office 365를 가리키면 완료됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-p127">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="161ac-p128">구독 서비스의 일부로 Office 365에서 확인된 모든 메일 사용 가능 도메인에 대해 Office 365 메시지 암호화(OME)를 설정합니다. MX 레코드가 Office 365를 가리키면 완료됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-p128">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="161ac-590">
  <strong>참고:</strong> MRS(사서함 복제 서비스)는 IRM(정보 권한 관리) 전자 메일을 해당 Exchange Online 사서함으로 마이그레이션하려고 합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-590">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="161ac-591">마이그레이션 후 보호된 콘텐츠를 읽는 기능은 클라이언트가 AD RMS(Active Directory Rights Managed Services) 서식 파일을 Azure RMS(Azure Rights Management Service)에 매핑하고 복사하는 방법에 따라 다릅니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-591">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="161ac-592">방화벽 포트 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-592">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="161ac-593">필요한 자동 검색, SPF(보낸 사람 정책 프레임워크), DKIM(DomainKeys 식별 메일), 도메인 기반 메시지 인증, 보고 및 적합성(DMARC) 및 MX 레코드(필요한 경우)를 비롯한 DNS 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-593">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="161ac-594">원본 메시징 환경과 Exchange Online 간 전자 메일 흐름 설정(필요한 경우)</span><span class="sxs-lookup"><span data-stu-id="161ac-594">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="161ac-595">원본 메시징 환경에서 Office 365로 메일 마이그레이션 수행</span><span class="sxs-lookup"><span data-stu-id="161ac-595">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="161ac-596">사서함 클라이언트(Windows용 Outlook, 웹용 Outlook, iOS 및 Android용 Outlook) 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-596">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="161ac-597">
  <strong>데이터 마이그레이션</strong>  </span><span class="sxs-lookup"><span data-stu-id="161ac-597">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="161ac-598">Office 365로의 데이터 마이그레이션에 FastTrack 혜택 사용에 대한 자세한 내용은 <a href="https://docs.microsoft.com/fasttrack/data-migration">데이터 마이그레이션을 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="161ac-598">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="161ac-599">원본 환경에는 다음 최소 수준 중 하나만 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-599">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-600">Exchange Server 2003 이후 버전을 사용하는 단일 또는 다중 Exchange 조직</span><span class="sxs-lookup"><span data-stu-id="161ac-600">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="161ac-601">단일 IMAP(Internet Message Access Protocol) 지원 전자 메일 환경</span><span class="sxs-lookup"><span data-stu-id="161ac-601">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="161ac-602">단일 G 제품군 환경(Gmail, 연락처 및 캘린더만)</span><span class="sxs-lookup"><span data-stu-id="161ac-602">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="161ac-603">Multi-Geo Capabilities에 대한 자세한 내용은 <a href="https://go.microsoft.com/fwlink/?linkid=872776">Exchange Online의 Multi-Geo Capabilities를 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="161ac-603">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="161ac-604">Office 365용 Project, Windows용 Outlook, iOS 및 Android용 Outlook, 비즈니스용 OneDrive 동기화 클라이언트, Power BI Desktop 및 비즈니스용 Skype와 같은 온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office의</a>시스템 요구 사항에 정의된 최소 수준 이상이 되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-604">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="161ac-605"><strong>Microsoft 정보 거버넌스</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-605"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="161ac-606">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-606">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-607">보존 레이블 및 정책 만들기 및 게시(E5에서만 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-607">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="161ac-608">레코드 관리(E5에서만 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-608">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="161ac-609">파일 계획 만들기 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-609">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="161ac-610">레코드 만들기 및 관리(이벤트 기반 레코드 포함)</span><span class="sxs-lookup"><span data-stu-id="161ac-610">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="161ac-611">검토.</span><span class="sxs-lookup"><span data-stu-id="161ac-611">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="161ac-612">

<strong> 준수 관리자</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-612">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="161ac-613">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-613">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="161ac-614">역할 유형 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-614">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="161ac-615">평가 추가 및 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-615">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="161ac-616">개선 작업을 구현하고 준수 점수에 어떤 영향을 미치는지 확인하여 준수를 평가합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-616">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="161ac-617">기본 제공 컨트롤 매핑 및 컨트롤 평가 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-617">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="161ac-618">평가 내에서 보고서 생성</span><span class="sxs-lookup"><span data-stu-id="161ac-618">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="161ac-619">

  <strong>다음은 범위를 벗어날 수 있는 예제입니다. </strong>  
</span><span class="sxs-lookup"><span data-stu-id="161ac-619">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="161ac-620">레코드 관리 파일 계획 개발</span><span class="sxs-lookup"><span data-stu-id="161ac-620">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="161ac-621">데이터 커넥터.</span><span class="sxs-lookup"><span data-stu-id="161ac-621">Data connectors.</span></span></li>
<li> <span data-ttu-id="161ac-622">SharePoint의 정보 아키텍처 개발.</span><span class="sxs-lookup"><span data-stu-id="161ac-622">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="161ac-623">사용자 지정 스크립팅 및 코딩.</span><span class="sxs-lookup"><span data-stu-id="161ac-623">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="161ac-624">디자인, 설계 및 타사 문서 검토.</span><span class="sxs-lookup"><span data-stu-id="161ac-624">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="161ac-625">E3에 대한 지원.</span><span class="sxs-lookup"><span data-stu-id="161ac-625">Support for E3.</span></span></li>
<li> <span data-ttu-id="161ac-626">산업 및 지역 규정 및 요구 사항을 준수합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-626">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="161ac-627">준수 관리자의 평가에 대한 권장 개선 작업의 실무를 구현합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-627">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>


</td>
<td><span data-ttu-id="161ac-628">일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 최소 시스템 요구 사항은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-628">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="161ac-629"><strong>Microsoft Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-629"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="161ac-630">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-630">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-631">데이터 분류(E3 및 E5에서 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-631">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="161ac-632">중요한 정보 유형(E3 및 E5에서 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-632">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="161ac-633">민감도 레이블 만들기(E3 및 E5에서 지원).</span><span class="sxs-lookup"><span data-stu-id="161ac-633">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="161ac-634">민감도 레이블 적용(E3 및 E5에서 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-634">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="161ac-635">교육 가능한 분류자(E5에서 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-635">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="161ac-636">콘텐츠 탐색기 및 활동 탐색기를 사용하여 데이터를 알 수 있습니다(E5에서 지원).</span><span class="sxs-lookup"><span data-stu-id="161ac-636">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="161ac-637">정책을 사용하여 레이블 게시(수동 및 자동)(E5에서 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-637">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="161ac-638">Windows 10 장치에 대한 끝점 DLP(데이터 손실 방지) 정책 만들기(E5에서 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-638">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="161ac-639">Microsoft Teams 채팅 및 채널에 대한 DLP 정책 만들기</span><span class="sxs-lookup"><span data-stu-id="161ac-639">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="161ac-640">

<strong> 준수 관리자</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-640">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="161ac-641">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-641">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="161ac-642">역할 유형 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-642">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="161ac-643">평가 추가 및 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-643">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="161ac-644">개선 작업을 구현하고 준수 점수에 어떤 영향을 미치는지 확인하여 준수를 평가합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-644">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="161ac-645">기본 제공 컨트롤 매핑 및 컨트롤 평가 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-645">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="161ac-646">평가 내에서 보고서 생성</span><span class="sxs-lookup"><span data-stu-id="161ac-646">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="161ac-647">

<strong> Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-647">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="161ac-648">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-648">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="161ac-649">테넌트 활성화 및 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-649">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="161ac-650">레이블 및 정책 만들기 및 설정(P1 및 P2에서 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-650">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="161ac-651">문서에 정보 보호 적용(P1 및 P2에서 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-651">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="161ac-652">Windows에서 실행되고 Azure Information Protection 클라이언트(P2에서 지원)를 사용하여 Office 앱(예: Word, PowerPoint, Excel 및 Outlook)에서 정보를 자동으로 분류하고 레이블을 지정합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-652">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="161ac-653">Azure Information Protection 스캐너를 사용하여 미사용 파일 검색 및 레이블 지정(P1 및 P2에서 지원)</span><span class="sxs-lookup"><span data-stu-id="161ac-653">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="161ac-654">Exchange Online 메일 흐름 규칙을 사용하여 전송 중인 전자 메일 모니터링</span><span class="sxs-lookup"><span data-stu-id="161ac-654">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
  
<span data-ttu-id="161ac-655">Microsoft Azure RMS(권한 관리 서비스), OME(Office 365 메시지 암호화) 및 DLP(데이터 손실 방지)를 사용하여 보호를 적용하려는 경우도 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-655">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="161ac-656"><strong>다음은 범위를 벗어날 수 있는 예제입니다. </strong></span><span class="sxs-lookup"><span data-stu-id="161ac-656"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="161ac-657">고객 키.</span><span class="sxs-lookup"><span data-stu-id="161ac-657">Customer key.</span></span></li>
<li><span data-ttu-id="161ac-658">중요한 정보 유형에 대한 사용자 지정 정규식(RegEx) 개발</span><span class="sxs-lookup"><span data-stu-id="161ac-658">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="161ac-659">키워드 사전 만들기 또는 수정</span><span class="sxs-lookup"><span data-stu-id="161ac-659">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="161ac-660">사용자 지정 스크립팅 및 코딩.</span><span class="sxs-lookup"><span data-stu-id="161ac-660">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="161ac-661">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="161ac-661">Azure Purview.</span></span></li>
<li> <span data-ttu-id="161ac-662">디자인, 설계 및 타사 문서 검토.</span><span class="sxs-lookup"><span data-stu-id="161ac-662">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="161ac-663">산업 및 지역 규정 및 요구 사항을 준수합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-663">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="161ac-664">준수 관리자의 평가에 대한 권장 개선 작업의 실무를 구현합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-664">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="161ac-665">일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 Azure Information Protection을 제외하고 최소 시스템 요구 사항은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-665">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="161ac-666"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-666"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="161ac-667">고객 선행 요구 사항 책임은 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-667">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="161ac-668">검사할 파일 공유 위치 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-668">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="161ac-669">승인된 분류법</span><span class="sxs-lookup"><span data-stu-id="161ac-669">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="161ac-670">키 관리에 대한 규정 제한 또는 요구 사항을 이해합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-670">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="161ac-671">Azure AD와 동기화된 프레미스 Active Directory에 대해 만들어진 서비스 계정입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-671">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="161ac-672">분류 및 보호를 위해 구성된 레이블입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-672">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="161ac-673">Azure Information Protection 스캐너에 대한 모든 선행조치가 준비됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-673">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="161ac-674">자세한 내용은 Azure Information Protection 통합 레이블 지정 스캐너 설치 및 배포를 위한 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites를 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="161ac-674">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="161ac-675">사용자 디바이스가 지원되는 운영 체제를 실행하고 있으며 필요한 필수 필수 장치가 설치되어 있는지 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-675">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="161ac-676">자세한 내용은 다음을 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-676">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="161ac-677"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">관리자 가이드: 사용자를 위한 Azure Information Protection 통합 레이블 클라이언트 설치</a>   </span><span class="sxs-lookup"><span data-stu-id="161ac-677"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="161ac-678"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">iOS 또는 Android용 Azure Information Protection 앱은 무엇입니까?</a>  </span><span class="sxs-lookup"><span data-stu-id="161ac-678"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="161ac-679">하이브리드 지원을 위한 AD RMS(Active Directory RMS) 커넥터를 포함하여 Azure RMS 커넥터 및 서버의 설치 및 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-679">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="161ac-680">배포에 이러한 옵션 중 하나만 필요한 경우 BYOK(Bring Your Own Key), DKE(이중 키 암호화)(통합 레이블 클라이언트만 해당) 또는 Hold Your Own Key (HYOK)(클래식 클라이언트만 해당)의 설치 및 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-680">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>.

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="161ac-681"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-681"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="161ac-682">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-682">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-683">Teams를 지원하기 위한 Exchange Online, SharePoint Online, Office 365 그룹 및 Azure AD에서 최소 요구 사항을 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-683">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="161ac-684">방화벽 포트 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-684">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="161ac-685">DNS 설정.</span><span class="sxs-lookup"><span data-stu-id="161ac-685">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="161ac-686">Office 365 테넌트에서 팀 확인이 가능합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-686">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="161ac-687">사용자 라이선스 사용 또는 사용 안 함.</span><span class="sxs-lookup"><span data-stu-id="161ac-687">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="161ac-688">Teams에 대한 네트워크 평가:</span><span class="sxs-lookup"><span data-stu-id="161ac-688">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-689">포트 및 끝점 검사</span><span class="sxs-lookup"><span data-stu-id="161ac-689">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="161ac-690">연결 품질 검사</span><span class="sxs-lookup"><span data-stu-id="161ac-690">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="161ac-691">대역폭 예상</span><span class="sxs-lookup"><span data-stu-id="161ac-691">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="161ac-692">Teams 앱 정책 구성(Teams 웹 앱, Teams 데스크톱 앱 및 iOS 및 Android 앱용 Teams)</span><span class="sxs-lookup"><span data-stu-id="161ac-692">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="161ac-693">해당하는 경우 다음에 대한 지침도 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-693">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-694">Microsoft Teams 룸 디바이스:</span><span class="sxs-lookup"><span data-stu-id="161ac-694">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="161ac-695"><a href="https://go.microsoft.com/fwlink/?linkid=2066478">팀 장치 카탈로그</a>에 나열된 지원되는 전화 및 회의실 디바이스에 필요한 온라인 계정 생성.</span><span class="sxs-lookup"><span data-stu-id="161ac-695">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="161ac-696">인증된 Microsoft Teams 룸 장치의 서비스 쪽 구성에 대한 원격 지원</span><span class="sxs-lookup"><span data-stu-id="161ac-696">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="161ac-697">오디오 회의 사용:</span><span class="sxs-lookup"><span data-stu-id="161ac-697">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="161ac-698">회의 브리지 기본 설정에 대한 조직 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-698">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="161ac-699">회의 브리지를 라이선스가 있는 사용자에게 할당</span><span class="sxs-lookup"><span data-stu-id="161ac-699">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="161ac-700">전화 시스템:</span><span class="sxs-lookup"><span data-stu-id="161ac-700">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-701">클라우드 음성 기본 설정에 대한 조직 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-701">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="161ac-702">통화 플랜<a href="https://go.microsoft.com/fwlink/?linkid=2066478">지침(사용 가능한 시장</a>):</span><span class="sxs-lookup"><span data-stu-id="161ac-702">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="161ac-703">라이선스가 있는 사용자에게 번호 할당</span><span class="sxs-lookup"><span data-stu-id="161ac-703">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="161ac-704">UI(사용자 인터페이스)를 통해 최대 999개의 지역 번호 이식 지침</span><span class="sxs-lookup"><span data-stu-id="161ac-704">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="161ac-705">999개가 넘는 번호를 지원하는 지역 번호 이식 SR(서비스 요청)</span><span class="sxs-lookup"><span data-stu-id="161ac-705">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="161ac-706">직접 라우팅 지침:</span><span class="sxs-lookup"><span data-stu-id="161ac-706">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-707">파트너 호스팅 시나리오의 직접 라우팅 디자인 또는 최대 10개 사이트에 대한 고객 배포 시나리오에 대한 조직 설정 지침입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-707">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="161ac-708">SBC(Session Border Controller) 구성 검토.</span><span class="sxs-lookup"><span data-stu-id="161ac-708">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="161ac-709">다이얼 플랜 구성에 대한 원격 지원.</span><span class="sxs-lookup"><span data-stu-id="161ac-709">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="161ac-710">음성 경로 구성.</span><span class="sxs-lookup"><span data-stu-id="161ac-710">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="161ac-711">미디어 우회 및 로컬 미디어 최적화.</span><span class="sxs-lookup"><span data-stu-id="161ac-711">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="161ac-712">권한 부여 팀 라이브 이벤트</span><span class="sxs-lookup"><span data-stu-id="161ac-712">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="161ac-713">조직 설정 및 Microsoft Stream에 통합</span><span class="sxs-lookup"><span data-stu-id="161ac-713">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="161ac-714">비즈니스용 Skype에서 Teams로의 전환에 대한 지침입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-714">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="161ac-715">Office 365용 Azure AD에서 사용 가능한 ID입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-715">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="161ac-716">SharePoint Online에 대해 사용하는 사용자.</span><span class="sxs-lookup"><span data-stu-id="161ac-716">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="161ac-717">Exchange 사서함이 있습니다(Exchange 하이브리드 구성의 온라인 및 사내).</span><span class="sxs-lookup"><span data-stu-id="161ac-717">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="161ac-718">Office 365 그룹에서 사용되도록 설정됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-718">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="161ac-719">
  <strong>참고:</strong> 사용자가 SharePoint Online 라이선스를 할당하고 사용하도록 설정하지 않은 경우 Office 365에서 비즈니스용 OneDrive 저장소를 사용할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-719">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="161ac-720">파일 공유는 채널에서 계속 작동하지만 사용자는 Office 365의 비즈니스용 OneDrive 저장소가 없는 채팅에서 파일을 공유할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-720">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="161ac-721">Teams는 SharePoint를 사내에서 지원하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-721">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="161ac-722">
  <strong>참고:</strong> 모든 사용자가 사서함을 Exchange Online에 두는 것이 가장 좋은 상태입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-722">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="161ac-723">사서함이 사내에 있는 사용자는 Azure AD Connect를 통해 해당 ID를 Office 365 디렉터리에 동기화해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-723">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="161ac-724">이러한 Exchange 하이브리드 고객의 경우 사용자의 사서함이 사내에 있는 경우 사용자는 커넥터를 추가하거나 구성할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-724">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="161ac-725">Microsoft Teams Windows 및 Mac 데스크톱 클라이언트용 설치 관리자는 <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>에서 다운로드할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-725">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="161ac-726"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-726"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="161ac-727">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-727">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-728">안전한 링크, 안전한 첨부 파일 및 피싱 방지 사용.</span><span class="sxs-lookup"><span data-stu-id="161ac-728">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="161ac-729">자동화, 조사 및 대응 구성.</span><span class="sxs-lookup"><span data-stu-id="161ac-729">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="161ac-730">공격 시뮬레이터 사용.</span><span class="sxs-lookup"><span data-stu-id="161ac-730">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="161ac-731">보고 및 위협 분석.</span><span class="sxs-lookup"><span data-stu-id="161ac-731">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="161ac-732">일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 최소 시스템 요구 사항은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-732">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="161ac-733"><strong>iOS 및 Android용 Outlook</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-733"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="161ac-734">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-734">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-735">Apple App Store를 Google Play에서 iOS 및 Android용 Outlook 다운로드</span><span class="sxs-lookup"><span data-stu-id="161ac-735">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="161ac-736">계정 구성 및 Exchange Online 사서함 액세스</span><span class="sxs-lookup"><span data-stu-id="161ac-736">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="161ac-737">Outlook 모바일 보안(자세한 내용은 <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Exchange Online에서 iOS</a> 및 Android용 Outlook 보안 참조).</span><span class="sxs-lookup"><span data-stu-id="161ac-737">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="161ac-738">Office 365용 Azure AD에서 사용 가능한 ID입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-738">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="161ac-739">Exchange Online이 구성되고 라이선스가 할당됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-739">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="161ac-740"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-740"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="161ac-741">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-741">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-742">Power BI 라이선스를 할당합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-742">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="161ac-743">Power BI Desktop 앱을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-743">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="161ac-744">Power BI Desktop과 같은 온라인 클라이언트 소프트웨어는 Microsoft <a href="https://go.microsoft.com/fwlink/?LinkID=723597">365</a>및 Office에 대한 시스템 요구 사항에 정의된 최소 수준 이상이 되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-744">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="161ac-745"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-745"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="161ac-746">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-746">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-747">Project Online이 사용하는 기본 SharePoint 기능 확인</span><span class="sxs-lookup"><span data-stu-id="161ac-747">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="161ac-748">테넌트에 Project Online 서비스 추가(사용자에게 구독 추가 포함)</span><span class="sxs-lookup"><span data-stu-id="161ac-748">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="161ac-749">ERP(Enterprise 자원 그룹) 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-749">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="161ac-750">첫 번째 프로젝트 만들기</span><span class="sxs-lookup"><span data-stu-id="161ac-750">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="161ac-751">Project for Office 365와 같은 온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365</a>및 Office에 대한 시스템 요구 사항에 정의된 최소 수준 이상에 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-751">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="161ac-752"><strong>Project Online Professional 및 Premium</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-752"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="161ac-753">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-753">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-754">배포 문제 해결</span><span class="sxs-lookup"><span data-stu-id="161ac-754">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="161ac-755">Microsoft 365 관리 센터 및 Windows PowerShell을 사용하여 최종 사용자 라이선스 할당</span><span class="sxs-lookup"><span data-stu-id="161ac-755">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="161ac-756">간편 실행을 사용하여 Office 365 포털에서 Project Online 데스크톱 클라이언트 설치</span><span class="sxs-lookup"><span data-stu-id="161ac-756">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="161ac-757">Office 365 배포 도구를 사용하여 업데이트 설정 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-757">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="161ac-758">Project Online 데스크톱 클라이언트를 위한 단일 사이트에 배포 서버 설정(Office 365 배포 도구용 configuration.xml 파일을 만드는 지침 포함)</span><span class="sxs-lookup"><span data-stu-id="161ac-758">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="161ac-759">Project Online 데스크톱 클라이언트을 Project Online Professional 또는 Project Online Premium에 연결합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-759">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="161ac-760">Project for Office 365와 같은 온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365</a>및 Office에 대한 시스템 요구 사항에 정의된 최소 수준 이상에 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-760">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="161ac-761"><strong>SharePoint Online 및 비즈니스용 OneDrive</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-761"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="161ac-762">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-762">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-763">DNS 설정.</span><span class="sxs-lookup"><span data-stu-id="161ac-763">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="161ac-764">방화벽 포트 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-764">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="161ac-765">사용자 및 라이선스 프로비전</span><span class="sxs-lookup"><span data-stu-id="161ac-765">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="161ac-766">SharePoint Online 관리자에 대해 사이트 만들기를 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-766">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="161ac-767">사이트 모음 계획</span><span class="sxs-lookup"><span data-stu-id="161ac-767">Planning site collections.</span></span></li>
<li><span data-ttu-id="161ac-768">콘텐츠 보호 및 권한 관리</span><span class="sxs-lookup"><span data-stu-id="161ac-768">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="161ac-769">SharePoint Online 기능 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-769">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="161ac-770">하이브리드 검색, 하이브리드 사이트, 하이브리드 분류, 콘텐츠 형식, 하이브리드 셀프 서비스 사이트 만들기(SharePoint Server 2013 전용), 확장된 앱 시작 관리자, 하이브리드 비즈니스용 OneDrive, 익스트라넷 사이트 등의 SharePoint 하이브리드 기능을 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-770">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="161ac-771">마이그레이션 방식</span><span class="sxs-lookup"><span data-stu-id="161ac-771">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="161ac-772">SharePoint 버전에 따라 비즈니스용 OneDrive에 대한 추가 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-772">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-773">통합 옵션 식별 및 사내 및 온라인 네트워크 인프라 및 대역폭 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-773">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="161ac-774">SharePoint Online 2013 SP1 설치(해당하는 경우), 동기화 및 ID 요구 사항을 계획 및 구현하고, 비즈니스용 OneDrive 동기화 클라이언트를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-774">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="161ac-775">모든 사용자(또는 단계적 롤아웃)에 대한 단일 출시 계획 및 구현</span><span class="sxs-lookup"><span data-stu-id="161ac-775">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="161ac-776">라이선스 할당, 내 사이트 및 개인 문서 라이브러리를 Office 365로 리디렉션(SharePoint Online 2013에 해당), OneDrive에 대한 액세스를 제어하기 위한 대상 설정을 지정합니다(SharePoint Online 2013에 해당).</span><span class="sxs-lookup"><span data-stu-id="161ac-776">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="161ac-777">알려진 폴더를 OneDrive로 리디렉션하거나 이동합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-777">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="161ac-778">비즈니스용 OneDrive 클라이언트 동기화 배포</span><span class="sxs-lookup"><span data-stu-id="161ac-778">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="161ac-779">
  <strong>데이터 마이그레이션</strong>  </span><span class="sxs-lookup"><span data-stu-id="161ac-779">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="161ac-780">Office 365로의 데이터 마이그레이션에 FastTrack 혜택 사용에 대한 자세한 내용은 <a href="https://docs.microsoft.com/fasttrack/data-migration">데이터 마이그레이션을 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="161ac-780">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="161ac-781"><strong>SharePoint 하이브리드의 경우:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="161ac-781"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="161ac-782">SharePoint 하이브리드 구성에는 하이브리드 검색, 사이트, 세분화, 콘텐츠 형식, 비즈니스용 OneDrive, 확장된 앱 시작 프로그램, 엑스트라넷 사이트 및 사내에서 단일 대상 SharePoint Online 환경으로 연결된 셀프 서비스 사이트 만들기 구성이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-782">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="161ac-783">
  <strong>참고:</strong> 셀프 서비스 사이트 만들기는 SharePoint 2013을 실행하는 사내 서버의 범위를 벗어났습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-783">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="161ac-784">SharePoint 하이브리드를 사용하도록 설정하려면 2013, 2016 또는 2019의 다음 사내 SharePoint Server 환경 중 하나를 설정해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-784">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="161ac-785">
  <strong>참고:</strong> SharePoint Server로의 사내 SharePoint 환경 업그레이드는 범위가 지정되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-785">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="161ac-786">Microsoft 파트너에게 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">지원을</a> 요청하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-786">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="161ac-787">자세한 내용은 SharePoint 하이브리드 기능에 대한 최소 공개 업데이트 <a href="https://go.microsoft.com/fwlink/?linkid=853548">수준을 참조하세요.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="161ac-787">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="161ac-788">
  <strong>참고:</strong> Multi-Geo Capabilities에 대한 자세한 내용은 <a href="https://go.microsoft.com/fwlink/?linkid=831056">Office 365의 OneDrive 및 SharePoint Online의 Multi-Geo 기능을 참조하세요.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="161ac-788">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="161ac-789"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-789"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="161ac-790">엔터프라이즈 서비스를 사용하도록 설정하기 위한 원격 Yammer 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-790">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="161ac-791">온라인 클라이언트 소프트웨어는 Microsoft 365 및 Office의 시스템 요구 사항에 정의된 최소 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">수준 이상이 되어야 합니다.</a></span><span class="sxs-lookup"><span data-stu-id="161ac-791">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="161ac-792">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="161ac-792">Enterprise Mobility + Security</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="161ac-793"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-793"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="161ac-794"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-794"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="161ac-795"><strong>원본 환경 기대치</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-795"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="161ac-796"><strong>Azure AD(Azure Active Directory) 및 Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-796"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="161ac-797">다음 시나리오에 대한 클라우드 ID 보안에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-797">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="161ac-798">

<strong>보안 기본 인프라</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="161ac-798">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="161ac-799">Azure MFA(다단계 인증)(클라우드 전용), Microsoft Authenticator 앱 및 Azure MFA 및 SSPR(셀프 서비스 암호 재설정)에 대한 결합 등록을 포함하여 ID에 대해 강력한 인증을 구성하고 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-799">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="161ac-800">Azure AD Premium이 아닌 고객의 경우 보안 기본값을 사용하여 ID를 보호하는 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-800">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="161ac-801">Azure AD 프리미엄 고객의 경우 조건부 액세스를 사용하여 ID를 보호하는 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-801">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="161ac-802">Azure AD 암호 보호를 사용하여 취약한 암호의 사용을 감지하고 차단합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-802">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="161ac-803">Azure AD 응용 프로그램 프록시를 사용하여 사내 웹앱에 대한 원격 액세스 보안</span><span class="sxs-lookup"><span data-stu-id="161ac-803">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="161ac-804">Azure Identity Protection을 사용하여 위험 기반 감지 및 수정을 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-804">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="161ac-805">사용자 지정 브랜드가 있는 로고, 텍스트 및 이미지를 포함하여 사용자 지정 로그인 화면 사용</span><span class="sxs-lookup"><span data-stu-id="161ac-805">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="161ac-806">Azure AD B2B를 사용하여 게스트 사용자와 앱 및 서비스를 안전하게 공유합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-806">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="161ac-807">RBAC(역할 기반 액세스 제어) 기본 제공 관리 역할을 사용하여 Office 365 관리자에 대한 액세스를 관리하고 권한 있는 관리자 계정 수를 줄입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-807">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="161ac-808">하이브리드 Azure AD 조인 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-808">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="161ac-809">Azure AD 조인 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-809">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="161ac-810">
  
<strong>모니터링 및 보고</strong>  
</span><span class="sxs-lookup"><span data-stu-id="161ac-810">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="161ac-811">Azure AD Connect Health를 사용하여 AD FS, Azure AD Connect 및 도메인 컨트롤러에 대한 원격 모니터링을 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-811">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="161ac-812">
  
<strong>거버넌스</strong>  
</span><span class="sxs-lookup"><span data-stu-id="161ac-812">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="161ac-813">Azure AD 권리 권한 관리를 사용하여 Azure AD ID 및 액세스 수명 주기를 대규모로 관리합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-813">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="161ac-814">Azure AD 액세스 검토를 사용하여 Azure AD 그룹 구성원 자격, 엔터프라이즈 앱 액세스 및 역할 할당 관리</span><span class="sxs-lookup"><span data-stu-id="161ac-814">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-815">Azure AD 사용 약관 검토</span><span class="sxs-lookup"><span data-stu-id="161ac-815">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-816">Azure AD Privileged Identity Management를 사용하여 권한 있는 관리자 계정에 대한 액세스 관리 및 제어</span><span class="sxs-lookup"><span data-stu-id="161ac-816">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="161ac-817">
  
<strong>자동화 및 효율성 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="161ac-817">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="161ac-818">Azure AD SSPR 사용.</span><span class="sxs-lookup"><span data-stu-id="161ac-818">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="161ac-819">사용자가 Azure AD 셀프 서비스 그룹 관리를 사용하여 자체 클라우드 보안 또는 Office 365 그룹을 만들고 관리할 수 있도록 허용합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-819">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="161ac-820">Azure AD 위임된 그룹 관리를 사용하여 엔터프라이즈 앱에 대한 위임된 액세스 관리</span><span class="sxs-lookup"><span data-stu-id="161ac-820">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="161ac-821">Azure AD 동적 그룹을 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-821">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="161ac-822">컬렉션을 사용하여 내 앱 포털에서 앱 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-822">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="161ac-823">Azure AD 및 Azure AD Premium 기능과의 통합을 방지하는 식별된 문제 수정을 포함하여 Azure AD Premium에 대한 준비를 하여, 해당 환경은 Azure AD Premium에 대해 준비되었습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-823">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="161ac-824"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="161ac-824"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="161ac-825">Azure Information Protection에 대한 자세한 내용은 보안 및 규정 <strong>준수의 Microsoft Information Protection을</strong> <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance"> 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-825">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="161ac-826"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-826"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="161ac-827">앱 및 장치에 대한 클라우드 기반 MDM(모바일 장치 관리) 및 MAM(모바일 앱 관리) 공급자로 Intune을 사용할 준비를 준비하는 방법에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-827">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="161ac-828">정확한 단계는 원본 환경에 따라 다르며 모바일 장치와 모바일 앱 관리 요구 사항에 기반합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-828">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="161ac-829">해당 단계는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-829">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-830">최종 사용자에게 라이선스 부여</span><span class="sxs-lookup"><span data-stu-id="161ac-830">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="161ac-831">Intune에서 사용할 ID를 구성하는 데는 Azure AD(클라우드 ID)를 활용합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-831">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="161ac-832">Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기</span><span class="sxs-lookup"><span data-stu-id="161ac-832">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="161ac-833">다음을 비롯한 관리 요구에 따라 MDM 기관 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-833">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-834">Intune이 유일한 MDM 솔루션인 경우 Intune을 MDM 기관으로 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-834">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="161ac-835">MDM 지침 제공:</span><span class="sxs-lookup"><span data-stu-id="161ac-835">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-836">MDM 관리 정책의 유효성을 검사하는 데 사용할 테스트 그룹 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-836">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="161ac-837">다음과 같은 MDM 관리 정책 및 서비스 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-837">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-838">웹 링크 또는 딥 링크를 통해 지원되는 각 플랫폼에 대한 앱 배포.</span><span class="sxs-lookup"><span data-stu-id="161ac-838">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="161ac-839">조건부 액세스 정책.</span><span class="sxs-lookup"><span data-stu-id="161ac-839">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="161ac-840">조직에 기존 인증 기관, 무선 네트워크 또는 VPN 인프라가 있는 경우 전자 메일, 무선 네트워크 및 VPN 프로필 배포.</span><span class="sxs-lookup"><span data-stu-id="161ac-840">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="161ac-841">Intune 데이터 웨어하우스에 연결</span><span class="sxs-lookup"><span data-stu-id="161ac-841">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="161ac-842">다음에 Intune 통합:</span><span class="sxs-lookup"><span data-stu-id="161ac-842">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-843">원격 지원을 위한 팀 뷰어(팀 뷰어 구독 필요)</span><span class="sxs-lookup"><span data-stu-id="161ac-843">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="161ac-844">MTD(Mobile Threat Defense) 파트너 솔루션(MTD 구독이 필요합니다.)</span><span class="sxs-lookup"><span data-stu-id="161ac-844">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="161ac-845">원격 비용 관리 솔루션(통신 비용 관리 솔루션 구독 필요)</span><span class="sxs-lookup"><span data-stu-id="161ac-845">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="161ac-846">각 지원되는 플랫폼의 장치를 Intune에 등록합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-846">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="161ac-847">앱 보호 지침 제공:</span><span class="sxs-lookup"><span data-stu-id="161ac-847">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-848">지원되는 각 플랫폼에 대한 Intune 앱 보호 정책 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-848">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="161ac-849">관리되는 앱에 대한 조건부 액세스 정책 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-849">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="161ac-850">앞서 언급한 MAM 정책을 통해 적절한 사용자 그룹을 대상으로 지정합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-850">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="161ac-851">관리되는 앱 사용 현황 보고서 사용.</span><span class="sxs-lookup"><span data-stu-id="161ac-851">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="161ac-852">레거시 PC 관리에서 Intune MDM으로의 마이그레이션 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-852">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="161ac-853">
  
</li>
</ul>
  
<strong>클라우드 연결</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-853">
  
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="161ac-854">Intune을 통해 기존 Configuration Manager 환경을 클라우드에 연결하기 위한 준비를 안내합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-854">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="161ac-855">정확한 단계는 원본 환경에 따라 다릅니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-855">The exact steps depend on your source environment.</span></span> <span data-ttu-id="161ac-856">해당 단계는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-856">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="161ac-857">최종 사용자에게 라이선스 부여</span><span class="sxs-lookup"><span data-stu-id="161ac-857">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="161ac-858">온-프레미스 Active Directory 및 클라우드 ID를 활용하여 Intune에서 사용할 ID 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-858">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="161ac-859">Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기</span><span class="sxs-lookup"><span data-stu-id="161ac-859">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="161ac-860">하이브리드 Azure AD 조인을 설정하는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-860">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="161ac-861">MDM 자동 등록을 위한 Azure AD 설정에 대한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-861">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="161ac-862">원격 인터넷 기반 장치 관리의 공동 관리를 위한 솔루션으로 사용될 때 클라우드 관리 게이트웨이를 설정하는 방법에 대한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-862">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="161ac-863">Intune으로 전환할 지원되는 작업 부하를 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-863">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="161ac-864">Intune에서 등록된 디바이스에서 Configuration Manager 클라이언트를 설치합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-864">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="161ac-865"><strong>iOS 및 Android용 Outlook 모바일을 안전하게 배포</strong> 조직에서 iOS 및 Android용 Outlook 모바일을 안전하게 배포하여 사용자에게 필요한 모든 앱이 설치되도록 하는 데 도움이 되는 지침을 제공할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-865"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="161ac-866">Intune을 통해 iOS 및 Android용 Outlook 모바일을 안전하게 배포하는 단계는 원본 환경에 따라 다를 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-866">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="161ac-867">여기에는 다음이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-867">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-868">Apple App Store 또는 Google Play 스토어를 통해 iOS 및 Android용 Outlook, Microsoft Authenticator 및 Intune 회사 포털 앱을 다운로드합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-868">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="161ac-869">설정에 대한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-869">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-870">Intune을 사용하여 iOS 및 Android용 Outlook, Microsoft Authenticator 및 Intune 회사 포털 앱 배포.</span><span class="sxs-lookup"><span data-stu-id="161ac-870">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="161ac-871">앱 보호 정책.</span><span class="sxs-lookup"><span data-stu-id="161ac-871">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="161ac-872">조건부 액세스 정책.</span><span class="sxs-lookup"><span data-stu-id="161ac-872">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="161ac-873">앱 구성 정책.</span><span class="sxs-lookup"><span data-stu-id="161ac-873">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="161ac-874">IT 관리자는 Intune을 사용하여 무선 네트워크 및 VPN 프로필 배포를 계획할 때 기존 인증 기관, 무선 네트워크 및 VPN 인프라가 프로덕션 환경에서 이미 작동하고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-874">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="161ac-875"><strong>참고:</strong>FastTrack 서비스 혜택에는 Intune에 대한 인증 기관, 무선 네트워크, VPN 인프라 또는 Apple MDM 푸시 인증서를 설정하거나 구성하기 위한 지원이 포함되어서는 안 됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-875"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="161ac-876"><strong>참고</strong>: 클라우드 연결 기능을 지원하는 데 필요한 최소 요구 사항에 맞게 Configuration Manager 사이트 서버 또는 Configuration Manager 클라이언트를 설정하거나 업그레이드하기 위한 지원은 FastTrack 서비스 혜택에 포함되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-876"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="161ac-877">이에 대한 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">지원은 Microsoft 파트너에게</a> 문의하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-877">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="161ac-878"><strong>Microsoft Defender ATP(Advanced Threat Protection)에 통합된 Intune</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-878"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="161ac-879"><strong>참고:</strong>Microsoft Defender ATP와 Intune을 통합하고 Windows 10 위험 수준 평가를 기반으로 장치 준수 정책을 만드는 데 도움을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-879"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="161ac-880">구매, 라이선스 또는 정품 인증에 대한 지원은 제공하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-880">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="161ac-881">이에 대한 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">지원은 Microsoft 파트너에게</a> 문의하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-881">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="161ac-882"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-882"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="161ac-883">IT 관리자는 하드웨어 공급 업체가 사용자를 대신하여 하드웨어 ID를 업로드하거나 Windows Autopilot 서비스로 업로드하는 방법으로 조직에 장치를 등록합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-883">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="161ac-884">Windows 10</span><span class="sxs-lookup"><span data-stu-id="161ac-884">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="161ac-885"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-885"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="161ac-886"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-886"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="161ac-887"><strong>원본 환경 기대치</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-887"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="161ac-888"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-888"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="161ac-889">Windows 7 Professional 및 Windows 8.1 Professional에서 Windows 10 Enterprise로 업그레이드하기 위한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-889">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="161ac-890">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-890">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-891">Windows 10 의도 이해</span><span class="sxs-lookup"><span data-stu-id="161ac-891">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="161ac-892">원본 환경 및 요구 사항 평가(Windows 10 배포를 지원하기 위해 Microsoft Endpoint Configuration Manager를 필요한 수준으로 업그레이드해야 합니다).</span><span class="sxs-lookup"><span data-stu-id="161ac-892">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="161ac-893">Microsoft Endpoint Configuration Manager 또는 Microsoft 365를 사용하여 Windows 10 Enterprise 및 Microsoft 365 앱을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-893">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="161ac-894">Windows 10 앱을 평가할 수 있는 권장 옵션입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-894">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="161ac-895">Desktop Analytics 배포 계획 생성을 통해 Desktop Analytics 및 지침을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-895">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="161ac-896">Configuration Manager의 Office 365 준비 대시보드 또는 Office용 독립 실행형 준비 Toolkit Microsoft 365 앱 배포 지원을 활용하여 Microsoft 365 앱 호환성 평가.</span><span class="sxs-lookup"><span data-stu-id="161ac-896">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="161ac-897">성공적인 배포를 위해 원본 환경을 최소 요구 사항까지 설정하기 위해 필요한 사항에 대한 재구성 검사 목록을 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-897">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="161ac-898">필요한 장치 하드웨어 요구 사항을 충족하는 경우 기존 장치에 대한 업그레이드 지침을 Windows 10 Enterprise로 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-898">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="161ac-899">기존 배포 움직임을 지원하기 위한 업그레이드 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-899">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="161ac-900">FastTrack은 Windows 10으로의 준비된 업그레이드를 위한 지침을 권장하고 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-900">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="161ac-901">Windows 정리 이미지 설치 및 Windows Autopilot 배포 시나리오에서도 지침을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-901">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="161ac-902">Windows 10 배포의 일부로 Configuration Manager를 사용하여 Microsoft 365 앱을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-902">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="161ac-903">조직에서 기존 Configuration Manager 환경 또는 Microsoft 365를 사용하여 Windows 10 Enterprise 및 Microsoft 365 앱을 최신으로 유지 하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-903">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="161ac-904">
  <strong>다음은 범위를 벗어날 수 있는 예제입니다. </strong>  
</span><span class="sxs-lookup"><span data-stu-id="161ac-904">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="161ac-905">Configuration Manager를 현재 분기로 업그레이드.</span><span class="sxs-lookup"><span data-stu-id="161ac-905">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="161ac-906">Windows 10 배포용 사용자 지정 이미지 만들기.</span><span class="sxs-lookup"><span data-stu-id="161ac-906">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="161ac-907">Windows 10 배포용 배포 스크립트 만들기 및 지원</span><span class="sxs-lookup"><span data-stu-id="161ac-907">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="161ac-908">Windows 10 시스템을 BIOS에서 UEFI(Unified Extensible Firmware Interface)로 변환.</span><span class="sxs-lookup"><span data-stu-id="161ac-908">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="161ac-909">Windows 10 보안 기능 활성화.</span><span class="sxs-lookup"><span data-stu-id="161ac-909">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="161ac-910">PXE(Preboot Execution Environment) 부팅을 위해 WDS(Windows Deployment Services) 구성.</span><span class="sxs-lookup"><span data-stu-id="161ac-910">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="161ac-911">Windows 10 이미지를 캡처하여 배포하는 데 MDT(Microsoft Deployment Toolkit) 사용.</span><span class="sxs-lookup"><span data-stu-id="161ac-911">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="161ac-912">USMT(User State Migration Tool) 사용.</span><span class="sxs-lookup"><span data-stu-id="161ac-912">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="161ac-913">Microsoft <a href="https://go.microsoft.com/fwlink/?linkid=2080150">파트너에게 문의하여</a> 이러한 서비스에 대한 지원을 요청하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-913">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="161ac-914">PC 업그레이드의 경우, 다음 요구 사항을 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-914">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-915">원본 OS: Windows 7 Enterprise 또는 Professional, Windows 8.1 Enterprise 또는 Professional.</span><span class="sxs-lookup"><span data-stu-id="161ac-915">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="161ac-916">장치: 데스크톱, 전자 필기장 또는 태블릿 폼 팩터입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-916">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="161ac-917">대상 OS: 창 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="161ac-917">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="161ac-918">인프라 업그레이드의 경우, 다음 요구 사항을 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-918">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-919">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="161ac-919">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="161ac-920">Configuration Manager 버전은 Windows 10 대상 버전에서 지원해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-920">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="161ac-921">자세한 내용은 <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager에서 Windows 10 지원</a>에서 Configuration Manager 지원 표를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-921">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="161ac-922"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-922"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="161ac-923">Microsoft Defender Advanced Threat Protection (ATP)는 엔터프라이즈 네트워크가 고급 위협을 방지, 탐지, 조사 및 대응하는 데 도움이 되도록 설계된 플랫폼입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-923">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="161ac-924">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-924">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-925">끝점을 보호하는 기술을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-925">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="161ac-926">끝점 보호 및 장치 제한 프로필 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-926">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="161ac-927">OS 버전 및 장치 관리(Intune, Microsoft Endpoint Configuration Manager, GOS(그룹 정책 개체) 및 타사 구성 포함) 및 Windows Defender AV 서비스 또는 기타 끝점 보안 소프트웨어의 상태를 평가합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-927">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="161ac-928">Windows AV 서비스 또는 기타 끝점 보안 소프트웨어의 상태 평가</span><span class="sxs-lookup"><span data-stu-id="161ac-928">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="161ac-929">네트워크 트래픽을 제한하는 Proxies 및 방화벽 평가</span><span class="sxs-lookup"><span data-stu-id="161ac-929">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="161ac-930">온보딩 끝점을 사용하여 ATP 에이전트 프로필을 배포하는 방법을 설명하여 Microsoft Defender ATP 서비스를 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-930">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="161ac-931">다음에 대한 배포 지침, 구성 지원 및 교육:</span><span class="sxs-lookup"><span data-stu-id="161ac-931">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="161ac-932">위협 및 취약성 관리.</span><span class="sxs-lookup"><span data-stu-id="161ac-932">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-933">공격 표면 감소.</span><span class="sxs-lookup"><span data-stu-id="161ac-933">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-934">차세대 보호.</span><span class="sxs-lookup"><span data-stu-id="161ac-934">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-935">끝점 감지 및 대응.</span><span class="sxs-lookup"><span data-stu-id="161ac-935">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-936">자동화된 조사 및 조치.</span><span class="sxs-lookup"><span data-stu-id="161ac-936">Automated investigation and remediation.</span></span>  
  </li>
<li> <span data-ttu-id="161ac-937">Microsoft Defender ATP(Windows E5 또는 Microsoft 365 E5 라이선스 필요)</span><span class="sxs-lookup"><span data-stu-id="161ac-937">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
<li>  
  <span data-ttu-id="161ac-938">보안 점수.</span><span class="sxs-lookup"><span data-stu-id="161ac-938">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="161ac-939">시뮬레이션 및 자습서 검토(예: 연습 시나리오, 가짜 맬웨어 및 자동화된 조사)</span><span class="sxs-lookup"><span data-stu-id="161ac-939">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="161ac-940">보고 및 위협 분석 기능 개요.</span><span class="sxs-lookup"><span data-stu-id="161ac-940">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="161ac-941">Office 365 ATP와 Microsoft Defender ATP 통합.</span><span class="sxs-lookup"><span data-stu-id="161ac-941">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="161ac-942">Microsoft Defender 보안 센터 포털 탐색.</span><span class="sxs-lookup"><span data-stu-id="161ac-942">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="161ac-943">다음 운영 체제는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-943">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="161ac-944">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="161ac-944">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-945">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="161ac-945">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-946">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="161ac-946">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-947">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="161ac-947">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-948">Windows Server Semi-Annual 채널(SAC) 버전 1803.</span><span class="sxs-lookup"><span data-stu-id="161ac-948">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-949">macOS 버전 10.13, 10.14 및 10.15.</span><span class="sxs-lookup"><span data-stu-id="161ac-949">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="161ac-950">
<strong>참고:</strong> 모든 Windows Server 버전은 최신 버전의 System Center Configuration Manager 2012(버전 1012 R2, 1511 또는 1602) 또는 Microsoft Endpoint Configuration Manager(버전 2002 이상)에서 관리해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-950">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="161ac-951"></li>
</ul>

<strong>다음은 범위를 벗어날 수 있는 예제입니다. </strong>  
</span><span class="sxs-lookup"><span data-stu-id="161ac-951"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="161ac-952">고객의 수정 활동에 대한 프로젝트 관리.</span><span class="sxs-lookup"><span data-stu-id="161ac-952">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="161ac-953">현장 지원.</span><span class="sxs-lookup"><span data-stu-id="161ac-953">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="161ac-954">지속적인 관리와 위협 대응.</span><span class="sxs-lookup"><span data-stu-id="161ac-954">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="161ac-955">다음 Microsoft Defender ATP 에이전트에 대한 온보딩 또는 구성:</span><span class="sxs-lookup"><span data-stu-id="161ac-955">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="161ac-956">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="161ac-956">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-957">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="161ac-957">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-958">Linux.</span><span class="sxs-lookup"><span data-stu-id="161ac-958">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-959">모바일 장치(Android 및 iOS).</span><span class="sxs-lookup"><span data-stu-id="161ac-959">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="161ac-960">VDI(가상 데스크톱 인프라)(영구적 또는 비영구적)</span><span class="sxs-lookup"><span data-stu-id="161ac-960">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="161ac-961">서버 온보드 및 구성:</span><span class="sxs-lookup"><span data-stu-id="161ac-961">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="161ac-962">오프라인 통신을 위한 프록시 서버 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-962">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-963">다운 수준 Configuration Manager 인스턴스 및 버전에서 Configuration Manager 배포 패키지 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-963">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-964">Azure 보안 센터에 서버 온보드</span><span class="sxs-lookup"><span data-stu-id="161ac-964">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-965">Configuration Manager에서 관리하지 않는 서버입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-965">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="161ac-966">macOS 온보더링 및 구성:</span><span class="sxs-lookup"><span data-stu-id="161ac-966">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="161ac-967">수동 Intune 기반 배포.</span><span class="sxs-lookup"><span data-stu-id="161ac-967">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-968">JAMF 기반 배포.</span><span class="sxs-lookup"><span data-stu-id="161ac-968">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="161ac-969">기타 MDM(모바일 장치 관리) 제품 기반 배포.</span><span class="sxs-lookup"><span data-stu-id="161ac-969">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-970">수동 배포.</span><span class="sxs-lookup"><span data-stu-id="161ac-970">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="161ac-971">다음 공격 표면 감소에 대한 기능:</span><span class="sxs-lookup"><span data-stu-id="161ac-971">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="161ac-972">하드웨어 기반 격리.</span><span class="sxs-lookup"><span data-stu-id="161ac-972">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-973">앱 컨트롤.</span><span class="sxs-lookup"><span data-stu-id="161ac-973">App control.</span></span>  
  </li>
<li> <span data-ttu-id="161ac-974">장치 제어.</span><span class="sxs-lookup"><span data-stu-id="161ac-974">Device control.</span></span></li>
<li>  
  <span data-ttu-id="161ac-975">악용 방지.</span><span class="sxs-lookup"><span data-stu-id="161ac-975">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-976">네트워크 방화벽.</span><span class="sxs-lookup"><span data-stu-id="161ac-976">Network firewall.</span></span>  
  </li>

<ul>
<li> <span data-ttu-id="161ac-977">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="161ac-977">Windows Hello</span></span></li>
<li> <span data-ttu-id="161ac-978">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="161ac-978">Credential Guard</span></span></li>
</ul>

</ul></li>
<li> <span data-ttu-id="161ac-979">BitLocker의 구성 또는 관리.</span><span class="sxs-lookup"><span data-stu-id="161ac-979">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="161ac-980">Microsoft 위협 전문가 등록 또는 구성.</span><span class="sxs-lookup"><span data-stu-id="161ac-980">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="161ac-981">API 또는 SIEM(보안 정보 및 이벤트 관리) 연결을 검토하는 구성 또는 교육</span><span class="sxs-lookup"><span data-stu-id="161ac-981">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="161ac-982">MTP(Microsoft 위협 방지) 등록 또는 구성.</span><span class="sxs-lookup"><span data-stu-id="161ac-982">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="161ac-983">고급 헌팅에 대한 교육 또는 지침.</span><span class="sxs-lookup"><span data-stu-id="161ac-983">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="161ac-984">Kusto 쿼리의 사용 또는 생성에 대한 교육 또는 지침입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-984">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="161ac-985">Microsoft <a href="https://go.microsoft.com/fwlink/?linkid=2080150">파트너에게 문의하여</a> 이러한 서비스에 대한 지원을 요청하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-985">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="161ac-986">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="161ac-986">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="161ac-987"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-987"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="161ac-988"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-988"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="161ac-989"><strong>원본 환경 기대치</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-989"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="161ac-990"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-990"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="161ac-991">Windows Virtual Desktop(데스크톱 및 앱 가상화 서비스)에 대한 온보드에 대한 배포 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-991">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="161ac-992">Windows Virtual Desktop은 Windows 10 다중 세션 환경을 활용하며 Microsoft 365용 통합 보안 및 관리를 통해 엔터프라이즈용 Microsoft 365 앱에 최적화되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-992">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="161ac-993">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-993">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="161ac-994">다음을 사용하여 Windows 10 Enterprise 다중 세션 및 엔터프라이즈용 Microsoft 365 앱을 사용하여 Windows Virtual Desktop 환경을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-994">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="161ac-995">Azure 마켓플레이스 이미지.</span><span class="sxs-lookup"><span data-stu-id="161ac-995">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="161ac-996">공유 이미지.</span><span class="sxs-lookup"><span data-stu-id="161ac-996">Shared image.</span></span></li>
<li><span data-ttu-id="161ac-997">ODT(Office Toolkit 배포)</span><span class="sxs-lookup"><span data-stu-id="161ac-997">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="161ac-998">FSLogix 구성:</span><span class="sxs-lookup"><span data-stu-id="161ac-998">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="161ac-999">프로필 컨테이너를 사용하여 FSLogix 에이전트 배포</span><span class="sxs-lookup"><span data-stu-id="161ac-999">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="161ac-1000">Office 컨테이너를 통해 FSLogix 에이전트 배포</span><span class="sxs-lookup"><span data-stu-id="161ac-1000">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="161ac-1001">콘텐츠 제외를 통해 FSLogix 폴더 구성</span><span class="sxs-lookup"><span data-stu-id="161ac-1001">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="161ac-1002">Microsoft Edge 배포.</span><span class="sxs-lookup"><span data-stu-id="161ac-1002">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="161ac-1003">Microsoft Teams 배포.</span><span class="sxs-lookup"><span data-stu-id="161ac-1003">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="161ac-1004">Windows Virtual Desktop 클라이언트를 사용하여 연결</span><span class="sxs-lookup"><span data-stu-id="161ac-1004">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="161ac-1005">

<strong>다음은 범위를 벗어날 수 있는 예제입니다.</strong>
</span><span class="sxs-lookup"><span data-stu-id="161ac-1005">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="161ac-1006">고객의 Windows Virtual Desktop 배포에 대한 프로젝트 관리</span><span class="sxs-lookup"><span data-stu-id="161ac-1006">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="161ac-1007">타사 앱 가상화 및 배포</span><span class="sxs-lookup"><span data-stu-id="161ac-1007">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="161ac-1008">사용자 지정 이미지.</span><span class="sxs-lookup"><span data-stu-id="161ac-1008">Custom images.</span></span></li>
<li><span data-ttu-id="161ac-1009">VMware 및 Citrix와 관련된 마이그레이션 및 시나리오</span><span class="sxs-lookup"><span data-stu-id="161ac-1009">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="161ac-1010">Linux 시나리오.</span><span class="sxs-lookup"><span data-stu-id="161ac-1010">Linux scenarios.</span></span></li>
<li><span data-ttu-id="161ac-1011">사용자 프로필 변환 또는 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="161ac-1011">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="161ac-1012">Microsoft <a href="https://go.microsoft.com/fwlink/?linkid=2080150">파트너에게 문의하여</a> 이러한 서비스에 대한 지원을 요청하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-1012">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="161ac-1013">다음이 이미 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1013">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="161ac-1014"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop 라이선스 요구 사항.</a></span><span class="sxs-lookup"><span data-stu-id="161ac-1014"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="161ac-1015">Azure 네트워킹:</span><span class="sxs-lookup"><span data-stu-id="161ac-1015">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="161ac-1016">VNET(가상 네트워크) 만들기 및 하위 연결.</span><span class="sxs-lookup"><span data-stu-id="161ac-1016">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="161ac-1017">방화벽 및 네트워크 보안 그룹</span><span class="sxs-lookup"><span data-stu-id="161ac-1017">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="161ac-1018">VPN 및 ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="161ac-1018">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="161ac-1019">사내에서 Azure로 라우팅</span><span class="sxs-lookup"><span data-stu-id="161ac-1019">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="161ac-1020">Windows Virtual Desktop에 대한 연결을 허용하는 방화벽 규칙</span><span class="sxs-lookup"><span data-stu-id="161ac-1020">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="161ac-1021">자세한 내용은 지원되는 원격 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">데스크톱 클라이언트를 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="161ac-1021">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="161ac-1022">Azure AD 일반 설정:</span><span class="sxs-lookup"><span data-stu-id="161ac-1022">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="161ac-1023">ID 전략(다음 세 가지 옵션 중 <i>하나만 사용할 수 있습니다.</i>
</span><span class="sxs-lookup"><span data-stu-id="161ac-1023">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="161ac-1024">Azure에서 Azure AD Connect가 있는 Active Directory.</span><span class="sxs-lookup"><span data-stu-id="161ac-1024">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="161ac-1025">VPN 또는 ExpressRoute를 통해 Azure AD Connect가 있는 Active Directory의 경우, 사내에서 Azure AD Connect를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1025">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="161ac-1026">AD DS(Active Directory 도메인 서비스).</span><span class="sxs-lookup"><span data-stu-id="161ac-1026">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="161ac-1027">App Assure</span><span class="sxs-lookup"><span data-stu-id="161ac-1027">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="161ac-1028"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-1028"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="161ac-1029"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-1029"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="161ac-1030"><strong>원본 환경 기대치</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-1030"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="161ac-1031"><strong>앱 보증</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-1031"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="161ac-1032">App Assure는 Windows 10 및 Microsoft 365 앱 호환성 문제를 해결하도록 설계된 서비스입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1032">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="161ac-1033">App Assure 서비스를 요청하면 적격 구독을 사용할 경우 추가 비용으로 유효한 앱 문제를 해결할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1033">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="161ac-1034">또한 Windows Virtual Desktop 및 Microsoft Edge를 배포할 때 호환성 문제가 있는 고객에게 지침을 제공하고 호환성 문제를 해결하기 위해 합리적인 노력을 다합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1034">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="161ac-1035">다음 Microsoft 제품에 배포된 앱에 대한 수정 지원을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1035">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="161ac-1036"><strong>Windows 10(ARM64 </strong> 장치 포함)</span><span class="sxs-lookup"><span data-stu-id="161ac-1036"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="161ac-1037"><strong>Microsoft 365 앱</strong>  </span><span class="sxs-lookup"><span data-stu-id="161ac-1037"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="161ac-1038"><strong>Microsoft Edge -</strong> 배포 지침은 Microsoft Edge 채널 <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">개요를 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="161ac-1038"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="161ac-1039"><strong>Windows Virtual Desktop</strong> - 자세한 내용은 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">Windows Virtual Desktop이란?</a> 및 Windows 10 Enterprise 다중 세션 <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">FAQ를 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="161ac-1039"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="161ac-1040">

<strong>다음은 범위를 벗어날 수 있는 예제입니다. </strong>  
</span><span class="sxs-lookup"><span data-stu-id="161ac-1040">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="161ac-1041">Windows 10 및 Microsoft 365 앱에서 작동하거나 작동하지 않는 기능을 확인하기 위한 앱 인벤토리 및 테스트.</span><span class="sxs-lookup"><span data-stu-id="161ac-1041">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="161ac-1042">이 프로세스에 관한 자세한 지침을 보려면 <a href="https://go.microsoft.com/fwlink/?linkid=2080140">데스크톱 배포 센터</a>를 방문하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-1042">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="161ac-1043">더 심화된 업그레이드 준비 평가에 관심이 있으신 경우 <a href="https://go.microsoft.com/fwlink/?linkid=2053818">최신 데스크톱 평가에 관한 고객 요청</a> 양식을 작성하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-1043">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="161ac-1044">타사 ISV 앱에서 Windows 10 호환성 및 지원 정책 연구</span><span class="sxs-lookup"><span data-stu-id="161ac-1044">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="161ac-1045">자세한 내용은 <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">데스크톱 분석</a>을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-1045">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="161ac-1046">앱 패키지 전용 서비스.</span><span class="sxs-lookup"><span data-stu-id="161ac-1046">App packaging-only services.</span></span> <span data-ttu-id="161ac-1047">그렇지만 App Assure 팀은 고객 환경에 배포될 수 있도록 하기 위해 WIndows 10에 대해 수정한 앱을 패키지로 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1047">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="161ac-1048">

<strong>고객 책임에는 다음이 포함됩니다.</strong>  
</span><span class="sxs-lookup"><span data-stu-id="161ac-1048">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="161ac-1049">앱 목록 만들기.</span><span class="sxs-lookup"><span data-stu-id="161ac-1049">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="161ac-1050">Windows 10 및 Microsoft 365 앱에서 앱의 유효성 검증.</span><span class="sxs-lookup"><span data-stu-id="161ac-1050">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="161ac-1051">
<strong>참고:</strong>  Microsoft는 소스 코드를 변경할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1051">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="161ac-1052">그러나 사용자 앱의 소스 코드를 사용할 수 있는 경우 App Assure 팀이 앱 개발자에게 지침을 제공할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1052">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="161ac-1053">Microsoft <a href="https://go.microsoft.com/fwlink/?linkid=2080150">파트너에게 문의하여</a> 이러한 서비스에 대한 지원을 요청하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-1053">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="161ac-1054"><strong>Windows 10 및 Microsoft 365 앱</strong>
</span><span class="sxs-lookup"><span data-stu-id="161ac-1054"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="161ac-1055">Windows 7, Windows 8.1, Office 2010 및 Office 2013에서 작동하는 앱은 Windows 10 및 Microsoft 365 앱에서도 작동합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1055">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="161ac-1056">
<strong>Windows 10 on ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="161ac-1056">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="161ac-1057">Windows 7, Office 2010 이상 버전에서 작동한 앱은 ARM64 장치의 Windows 10 및 Microsoft 365 앱에서도 작동합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1057">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="161ac-1058">
  <strong>참고:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="161ac-1058">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="161ac-1059">x64(64비트) 에뮬ATION은 <a href="https://insider.windows.com/">Windows Insider Program에</a>참여하는 고객을 위해 미리 보기에서 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1059">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="161ac-1060">Windows 10 버전 2004 이상을 사용하는 Windows가 아닌 고객의 경우 ARM64 Photoshop은 OpenCL 및 OpenGL 호환성 팩을 사용하여 <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">지원됩니다.</a></span><span class="sxs-lookup"><span data-stu-id="161ac-1060">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="161ac-1061">Windows Insider Program의 고객은 추가 앱에 사용할 OpenCL 및 OpenGL 호환성 팩의 Insider 버전을 다운로드할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1061">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="161ac-1062">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="161ac-1062">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="161ac-1063">웹앱 또는 사이트가 Internet Explorer 11, 지원되는 Google Chrome 또는 모든 버전의 Microsoft Edge에서 작업하는 경우 Microsoft Edge에서도 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1063">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-1064">웹이 지속적으로 진화하고 있는 경우 Microsoft Edge에 대해 게시된 알려진 사이트 호환성에 영향을 미치는 변경 사항 목록을 <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">검토해야 합니다.</a></span><span class="sxs-lookup"><span data-stu-id="161ac-1064">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="161ac-1065">
  <strong>Windows Virtual Desktop </strong>  
</span><span class="sxs-lookup"><span data-stu-id="161ac-1065">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="161ac-1066">Windows Server RDSH (원격 데스크톱 세션 호스트)에서 실행되는 가상화된 앱도 Windows Virtual Desktop의 일부로 Windows 10 Enterprise 멀티 세션에서 실행됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1066">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-1067">Windows 7 또는 Windows 10 VDI(가상 데스크톱 인프라) 환경에서 실행되는 앱은 Windows Virtual Desktop의 일부로 Windows 7 Enterprise 및 Windows 10 Enterprise에서도 실행됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1067">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-1068">Windows 7 또는 Windows 10 클라이언트 장치에서 실행되는 앱도 Windows Virtual Desktop의 일부로 Windows 7 Enterprise 및 Windows 10 Enterprise에서 실행됩니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1068">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="161ac-1069">
  <strong>참고:</strong> Windows 10 Enterprise 다중 세션 호환성 제외 및 제한은 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1069">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="161ac-1070">제한된 하드웨어 리디렉션.</span><span class="sxs-lookup"><span data-stu-id="161ac-1070">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-1071">A/V-집약적인 앱은 줄어든 용량으로 실행될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1071">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="161ac-1072">16비트 앱은 64비트 Windows Virtual Desktop에서 지원되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1072">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="161ac-1073">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="161ac-1073">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="161ac-1074"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-1074"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="161ac-1075"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-1075"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="161ac-1076"><strong>원본 환경 기대치</strong></span><span class="sxs-lookup"><span data-stu-id="161ac-1076"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="161ac-1077"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="161ac-1077"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="161ac-1078">다음에 대한 원격 배포 및 채택 지침과 호환성 지원을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1078">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="161ac-1079">Microsoft Endpoint Manager(Microsoft Endpoint Configuration Manager 또는 Intune)를 통해 Windows 10에 Microsoft Edge 배포</span><span class="sxs-lookup"><span data-stu-id="161ac-1079">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="161ac-1080">Microsoft Edge 구성(그룹 정책 또는 Intune 앱 구성 및 앱 정책 사용)</span><span class="sxs-lookup"><span data-stu-id="161ac-1080">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="161ac-1081">Internet Explorer 모드로 사용할 수 있는 사이트 목록 인벤토리를 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1081">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="161ac-1082">기존 엔터프라이즈 Internet Explorer 모드로 설정</span><span class="sxs-lookup"><span data-stu-id="161ac-1082">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="161ac-1083">자세한 내용은 관련 <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">FastTrack을 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="161ac-1083">(For more information, see <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>).</span></span> <span data-ttu-id="161ac-1084">또한 Internet Explorer 또는 Google Chrome과 함께 작동하는 웹 앱 또는 사이트가 있는 경우 추가 비용으로 문제를 해결하기 위한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1084">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="161ac-1085">App Assure에 대한 호환성 지원을 요청하기 위해 <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack</a> 포털에 로그인하여 계약을 시작하세요.</span><span class="sxs-lookup"><span data-stu-id="161ac-1085">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="161ac-1086">Microsoft Search 책갈피에 대한 Edge 채택 및 구성 지침 계획 지침</span><span class="sxs-lookup"><span data-stu-id="161ac-1086">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="161ac-1087">

<strong>다음은 범위를 벗어날 수 있는 예제입니다. </strong>  
</span><span class="sxs-lookup"><span data-stu-id="161ac-1087">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="161ac-1088">고객의 Microsoft Edge 배포에 대한 프로젝트 관리입니다.</span><span class="sxs-lookup"><span data-stu-id="161ac-1088">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="161ac-1089">현장 지원.</span><span class="sxs-lookup"><span data-stu-id="161ac-1089">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
