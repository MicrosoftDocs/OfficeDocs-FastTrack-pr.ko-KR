---
title: 제품 및 기능
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/27/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: 이 항목에는 FastTrack에서 지원하는 작업 시나리오와 시작하기 전에 필요한 원본 환경 기대치에 대한 세부 정보가 포함되어 있습니다. 현재 설정에 따라 성공적인 온보드를 위한 최소 요구 사항까지 원본 환경을 개선하는 재구성 계획을 세우기 위해 함께 작업합니다.
ms.openlocfilehash: abbc97a7b2d70b0b0111f1cbe96904bbe552e463
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016690"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="23392-104">제품 및 기능</span><span class="sxs-lookup"><span data-stu-id="23392-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="23392-105">FastTrack에서 지원하는 서비스 및 시나리오</span><span class="sxs-lookup"><span data-stu-id="23392-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="23392-106">이 항목에는 FastTrack에서 지원하는 작업 시나리오와 시작하기 전에 필요한 원본 환경 기대치에 대한 세부 정보가 포함되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="23392-107">현재 설정에 따라 성공적인 온보드를 위한 최소 요구 사항까지 원본 환경을 개선하는 재구성 계획을 세우기 위해 함께 작업합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="23392-108">FastTrack은 먼저 핵심 기능(모든 사용자에 대해 공통)을 제공한 다음 적합한 각 서비스를 온보더링하는 데 도움이 Microsoft Online Services 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="23392-109">일반</span><span class="sxs-lookup"><span data-stu-id="23392-109">General</span></span>](#general)
  - [<span data-ttu-id="23392-110">보안 및 규정 준수</span><span class="sxs-lookup"><span data-stu-id="23392-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="23392-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="23392-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="23392-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="23392-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="23392-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="23392-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="23392-114">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="23392-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="23392-115">App Assure</span><span class="sxs-lookup"><span data-stu-id="23392-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="23392-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="23392-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="23392-117">Office 365 미국 정부에 대한 원본 환경 기대치에 대한 정보는 [Office 365 미국 정부에 대한 원본 환경 기대치](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="23392-118">일반 사항</span><span class="sxs-lookup"><span data-stu-id="23392-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="23392-119"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="23392-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="23392-120"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="23392-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="23392-121"><strong>원본 환경 기대치</strong></span><span class="sxs-lookup"><span data-stu-id="23392-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="23392-122"><strong>핵심 온보딩</strong></span><span class="sxs-lookup"><span data-stu-id="23392-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="23392-123">서비스 프로비전, 테넌트 및 ID 통합과 관련된 핵심 온보드에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="23392-124">또한 보안, 네트워크 연결 및 규정 준수에 대한 토론을 포함하여 Exchange Online, SharePoint Online 및 Microsoft Teams와 같은 온보더링 서비스에 대한 기초를 제공하기 위한 단계도 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">포함되어 있습니다.</a></span><span class="sxs-lookup"><span data-stu-id="23392-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="23392-125">하나 이상의 적합한 서비스에 대한 온보딩은 핵심 온보딩이 완료되면 시작됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="23392-126"></li>
</ul>  

<strong> ID 통합 </strong></span><span class="sxs-lookup"><span data-stu-id="23392-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="23392-127">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="23392-128">Azure AD Connect(단일 포리스트 또는 다중 포리스트) 및 라이선스(그룹 기반 라이선싱 포함)를 설치 및 구성하는 작업을 포함하여 Azure AD(Azure Active Directory)에 동기화하기 위한 On-premises Active Directory ID 준비</span><span class="sxs-lookup"><span data-stu-id="23392-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="23392-129">그룹 기반 라이선싱 사용을 포함하여 대량 가져오기 및 라이선스를 포함한 클라우드 ID 만들기</span><span class="sxs-lookup"><span data-stu-id="23392-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="23392-130">클라우드 여정, 암호 해시 동기화, 통과 인증 또는 AD FS(Active Directory Federation Services)에 대한 올바른 인증 방법을 선택하고 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="23392-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="23392-131">Azure AD Connect 도구와 동기화된 단일 Active Directory 포리스트 및 ID를 사용하는 고객에 대해 AD FS를 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="23392-131">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="23392-132">이렇게 하려면 Windows Server 2012 R2 Active Directory Federation Services 2.0 이상이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-132">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="23392-133">암호 해시 동기화 또는 통과 인증을 사용하여 AD FS에서 Azure AD로 인증 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="23392-133">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="23392-134">SSO(Single Sign-On)를 위해 사전 통합된 앱(예: Azure AD 갤러리 SaaS(Software-as-a-Service) 앱)을 AD FS에서 Azure AD로 마이그레이션합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-134">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="23392-135">Azure AD 갤러리에서 SaaS 앱과 SSO를 통합할 수 있도록 설정</span><span class="sxs-lookup"><span data-stu-id="23392-135">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="23392-136">앱 통합 자습서 목록에 나열된 미리 통합된 SaaS 앱에 대해 자동 사용자 프로비전을 사용하도록 설정(Azure AD 갤러리 SaaS 앱 및 아웃바운드 프로비저닝으로 제한) <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list"></a></span><span class="sxs-lookup"><span data-stu-id="23392-136">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="23392-137"><strong>네트워크 사용 설정 </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="23392-137"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="23392-138">FastTrack 혜택의 일부로 Microsoft 365의 최고 수준의 성능을 보장하기 위해 클라우드 서비스에 연결하는 모범 사례를 활용하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-138">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="23392-139"><strong>Active Directory 포리스트</strong> 다음 포리스트 구성을 통해 포리스트 기능 수준이 Windows Server 2003 이상으로 설정됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-139"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="23392-140">단일 Active Directory 포리스트.</span><span class="sxs-lookup"><span data-stu-id="23392-140">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="23392-141">단일 Active Directory 계정 포리스트 및 리소스 포리스트(Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype) 토폴로지</span><span class="sxs-lookup"><span data-stu-id="23392-141">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="23392-142">여러 개의 Active Directory 계정 포리스트 및 리소스 포리스트(Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype) 토폴로지</span><span class="sxs-lookup"><span data-stu-id="23392-142">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="23392-143">포리스트 중 하나가 Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype가 있는 중앙 집중식 Active Directory 계정 포리스트인 여러 Active Directory 계정 포리스트</span><span class="sxs-lookup"><span data-stu-id="23392-143">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="23392-144">각각이 자체 Exchange 조직을 갖는 다중 Active Directory 계정 포리스트</span><span class="sxs-lookup"><span data-stu-id="23392-144">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="23392-145">필요한 경우 테넌트 구성 및 Azure Active Directory와의 통합에 필요한 작업</span><span class="sxs-lookup"><span data-stu-id="23392-145">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="23392-146">
  <strong>중요</strong>  </span><span class="sxs-lookup"><span data-stu-id="23392-146">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="23392-147">다중 포리스트 Active Directory 시나리오의 경우 Lync 2010, Lync 2013 또는 비즈니스용 Skype가 배포된 경우 Exchange와 동일한 Active Directory 포리스트에 배포해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-147">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="23392-148">Exchange 다중 하이브리드 구성에서 여러 Exchange 조직과 함께 여러 Active Directory 포리스트를 구현하는 경우 원본 포리스트 간의 공유 UPN(사용자 계정 이름) 네임스페이스는 지원되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-148">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="23392-149">Exchange 조직 간의 기본 SMTP 네임스페이스도 구분해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-149">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="23392-150">자세한 내용은 여러 <a href="https://go.microsoft.com/fwlink/?linkid=845444">Active Directory 포리스트가 있는 하이브리드 배포를 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="23392-150">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="23392-151">모든 다중 포리스트 구성에서 AD FS(Active Directory Federation Services) 배포의 범위를 벗어날 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-151">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="23392-152">이에 대한 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">지원은 Microsoft 파트너에게</a> 문의하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-152">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23392-153"><strong>Microsoft 365 앱</strong></span><span class="sxs-lookup"><span data-stu-id="23392-153"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="23392-154">다음에 대한 원격 배포 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-154">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-155">배포 문제 해결</span><span class="sxs-lookup"><span data-stu-id="23392-155">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="23392-156">Microsoft 365 관리 센터 및 Windows PowerShell을 사용하여 최종 사용자 및 디바이스 기반 라이선스 할당</span><span class="sxs-lookup"><span data-stu-id="23392-156">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="23392-157">간편 실행을 사용하여 Office 365 포털에서 Microsoft 365 앱 설치</span><span class="sxs-lookup"><span data-stu-id="23392-157">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="23392-158">iOS 또는 Android 장치에 Office Mobile 앱(에: Outlook Mobile, Word Mobile, Excel Mobile 및 PowerPoint Mobile) 설치</span><span class="sxs-lookup"><span data-stu-id="23392-158">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="23392-159">Office 365 배포 도구를 사용하여 업데이트 설정 구성</span><span class="sxs-lookup"><span data-stu-id="23392-159">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="23392-160">로컬 또는 클라우드 설치의 선택 및 설치</span><span class="sxs-lookup"><span data-stu-id="23392-160">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="23392-161">배포 패티지를 구성하기 위해 Office 사용자 지정 도구 또는 네이티브 XML을 사용하여 Office 배포 도구 구성 XML 작성</span><span class="sxs-lookup"><span data-stu-id="23392-161">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="23392-162">Microsoft Endpoint Configuration Manager를 사용하여 배포(Endpoint Configuration Manager 패키지 생성에 대한 지원 포함)</span><span class="sxs-lookup"><span data-stu-id="23392-162">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="23392-163">또한 이전 버전의 Office와 함께 작동한 매크로나 추가 기능을 사용할 경우 호환성 문제가 있는 경우 App Assure 프로그램을 통해 추가 비용으로 호환성 문제를 해결하기 위한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-163">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="23392-164">자세한 내용은 Windows <a href="#windows-10">10의</a> <strong>App Assure</strong> 부분을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-164">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="23392-165">온라인 클라이언트 소프트웨어는 Microsoft 365 및 Office의 시스템 요구 사항에 정의된 최소 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">수준 이상이 되어야 합니다.</a></span><span class="sxs-lookup"><span data-stu-id="23392-165">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23392-166"><strong>네트워크 상태</strong></span><span class="sxs-lookup"><span data-stu-id="23392-166"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="23392-167">Microsoft는 사용자 환경에서 조직의 사이트가 네트워크 연결의 Microsoft의 원칙에 얼마나 부합하는지 보여주는 주요 네트워크 연결 데이터를 획득하고 해석하는 원격 지침을 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">제공합니다.</a></span><span class="sxs-lookup"><span data-stu-id="23392-167">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="23392-168">그러면 마이그레이션 속도, 사용자 환경, 서비스 성능 및 안정성에 직접적인 영향을 미치는 네트워크 점수가 강조 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-168">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="23392-169">또한 네트워크 점수를 개선하는 데 도움이 될 수 있도록 이 데이터로 강조 표시된 모든 수정 단계를 안내합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-169">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="23392-170">Microsoft 365 관리 센터 액세스.</span><span class="sxs-lookup"><span data-stu-id="23392-170">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="23392-171">최신 버전의 Microsoft 365 앱이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-171">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="23392-172"><a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365</a>관리 센터(미리 보기)의 네트워크 성능 권장 사항에 따라 사용하도록 설정된 위치 서비스</span><span class="sxs-lookup"><span data-stu-id="23392-172">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="23392-173">보안 및 규정 준수</span><span class="sxs-lookup"><span data-stu-id="23392-173">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="23392-174"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="23392-174"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="23392-175"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="23392-175"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="23392-176"><strong>원본 환경 기대치</strong></span><span class="sxs-lookup"><span data-stu-id="23392-176"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="23392-177"><strong>Azure AD(Azure Active Directory) 및 Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="23392-177"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="23392-178">다음 시나리오에서 클라우드 ID를 보호하는 데 필요한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-178">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="23392-179">

<strong>보안 기본 인프라</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="23392-179">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="23392-180">Azure MFA(Multi-Factor Authentication)(클라우드 전용), Microsoft Authenticator 앱 및 Azure MFA 및 SSPR(셀프 서비스 암호 재설정)에 대한 결합 등록을 포함하여 ID에 대해 강력한 인증을 구성하고 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="23392-180">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="23392-181">Azure AD Premium이 아닌 고객의 경우 보안 기본값을 사용하여 ID를 보호할 수 있는 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-181">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="23392-182">Azure AD 프리미엄 고객의 경우 조건부 액세스로 ID를 보호할 수 있는 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-182">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="23392-183">Azure AD 암호 보호를 사용하여 취약한 암호의 사용을 감지하고 차단합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-183">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="23392-184">Azure AD 응용 프로그램 프록시를 사용하여 프레미스 웹앱에 대한 원격 액세스 보안</span><span class="sxs-lookup"><span data-stu-id="23392-184">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="23392-185">Azure ID 보호를 사용하여 위험 기반 검색 및 수정을 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="23392-185">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="23392-186">사용자 지정 브랜드가 있는 로고, 텍스트 및 이미지를 포함하여 사용자 지정 로그인 화면 사용</span><span class="sxs-lookup"><span data-stu-id="23392-186">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="23392-187">Azure AD B2B를 사용하여 게스트 사용자와 앱 및 서비스를 안전하게 공유합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-187">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="23392-188">RBAC(역할 기반 액세스 제어) 기본 제공 관리 역할을 사용하여 Office 365 관리자에 대한 액세스를 관리하고 권한 있는 관리자 계정 수를 줄입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-188">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="23392-189">하이브리드 Azure AD 조인 구성</span><span class="sxs-lookup"><span data-stu-id="23392-189">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="23392-190">Azure AD 가입 구성</span><span class="sxs-lookup"><span data-stu-id="23392-190">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="23392-191">
  
<strong>모니터링 및 보고</strong>  
</span><span class="sxs-lookup"><span data-stu-id="23392-191">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="23392-192">Azure AD Connect Health를 사용하여 AD FS, Azure AD Connect 및 도메인 컨트롤러에 대한 원격 모니터링을 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="23392-192">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="23392-193">
  
<strong>거버넌스</strong>  
</span><span class="sxs-lookup"><span data-stu-id="23392-193">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="23392-194">Azure AD 권리 부여 관리를 사용하여 Azure AD ID 및 액세스 수명 주기를 대규모로 관리합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-194">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="23392-195">Azure AD 액세스 검토를 사용하여 Azure AD 그룹 구성원 자격, 엔터프라이즈 앱 액세스 및 역할 할당 관리</span><span class="sxs-lookup"><span data-stu-id="23392-195">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-196">Azure AD 사용 약관 검토</span><span class="sxs-lookup"><span data-stu-id="23392-196">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-197">Azure AD Privileged Identity Management를 사용하여 권한 있는 관리자 계정에 대한 액세스를 관리하고 제어합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-197">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="23392-198">
  
<strong>자동화 및 효율성 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="23392-198">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="23392-199">Azure AD SSPR 사용</span><span class="sxs-lookup"><span data-stu-id="23392-199">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="23392-200">사용자가 Azure AD 셀프 서비스 그룹 관리를 사용하여 자체 클라우드 보안 또는 Office 365 그룹을 만들고 관리할 수 있도록 허용</span><span class="sxs-lookup"><span data-stu-id="23392-200">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="23392-201">Azure AD 위임된 그룹 관리를 사용하여 엔터프라이즈 앱에 대한 위임된 액세스 관리</span><span class="sxs-lookup"><span data-stu-id="23392-201">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="23392-202">Azure AD 동적 그룹을 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="23392-202">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="23392-203">컬렉션을 사용하여 내 앱 포털에서 앱 구성</span><span class="sxs-lookup"><span data-stu-id="23392-203">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="23392-204">Azure AD 및 Azure AD Premium 기능과의 통합을 방지하는 식별된 문제의 수정을 포함하여 Azure AD Premium에 대한 On-premises Active Directory 및 해당 환경이 준비되었습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-204">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23392-205"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="23392-205"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="23392-206">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-206">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-207">테넌트 활성화 및 구성</span><span class="sxs-lookup"><span data-stu-id="23392-207">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="23392-208">레이블과 정책 만들기 및 설정</span><span class="sxs-lookup"><span data-stu-id="23392-208">Creating and setting up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="23392-209">문서에 정보 보호 적용</span><span class="sxs-lookup"><span data-stu-id="23392-209">Applying information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="23392-210">Azure Information Protection 클라이언트를 사용하여 Windows에서 실행 중인 Office 앱(Word, PowerPoint, Excel, Outlook 등)에서 자동으로 정보 분류 및 레이블 지정</span><span class="sxs-lookup"><span data-stu-id="23392-210">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="23392-211">Azure Information Protection 스캐너를 사용하여 미사용 파일 검색 및 레이블 지정</span><span class="sxs-lookup"><span data-stu-id="23392-211">Discovering and labeling files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="23392-212">Exchange Online 메일 흐름 규칙을 사용하여 전송 중인 전자 메일 모니터링</span><span class="sxs-lookup"><span data-stu-id="23392-212">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="23392-213">Microsoft Azure RMS(권한 관리 서비스), OME(Office 365 메시지 암호화) 및 DLP(데이터 손실 방지)를 사용하여 보호를 적용하려는 경우도 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-213">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="23392-214">고객 선행 요구 사항 책임은 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-214">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="23392-215">검사할 파일 공유 위치 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-215">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="23392-216">승인된 분류 분류입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-216">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="23392-217">키 관리에 대한 규정 제한 또는 요구 사항을 이해합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-217">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="23392-218">Azure AD와 동기화된,프레미스 Active Directory에 대해 만들어진 서비스 계정입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-218">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="23392-219">분류 및 보호를 위해 구성된 레이블입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-219">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="23392-220">Azure Information Protection 스캐너에 대한 모든 선행이 준비됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-220">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="23392-221">자세한 내용은 Azure Information Protection 통합 레이블 지정 스캐너를 설치 및 배포하기 위한 선행 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">구성을 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="23392-221">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="23392-222">사용자 장치가 지원되는 운영 체제를 실행하고 있으며 필수 필수가 설치되어 있는지 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-222">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="23392-223">자세한 내용은 다음을 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-223">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="23392-224"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">관리자 가이드: 사용자를 위한 Azure Information Protection 통합 레이블 지정 클라이언트 설치</a>   </span><span class="sxs-lookup"><span data-stu-id="23392-224"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="23392-225"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">iOS 또는 Android용 Azure Information Protection 앱은 무엇입니까?</a>  </span><span class="sxs-lookup"><span data-stu-id="23392-225"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="23392-226">하이브리드 지원을 위한 AD RMS(Active Directory RMS) 커넥터를 포함하여 Azure RMS 커넥터 및 서버의 설치 및 구성</span><span class="sxs-lookup"><span data-stu-id="23392-226">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="23392-227">배포에 이러한 옵션 중 하나를 필요로 하는 경우 BYOK(Bring Your Own Key), DKE(이중 키 암호화)(통합 레이블 지정 클라이언트만 해당) 또는 HYOK(Own Key)를 설치 및 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-227">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="23392-228"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="23392-228"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="23392-229">Microsoft 365 Defender는 엔드포인트, ID, 전자 메일 및 앱에 대한 감지, 방지, 조사 및 대응을 기본적으로 조정하여 정교한 공격으로부터 통합된 보호를 제공하는 통합 사전 및 사후 위반 엔터프라이즈 방어 제품군입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-229">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="23392-230">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-230">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="23392-231">Microsoft 365 보안 센터의 개요를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-231">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="23392-232">전체 공격 범위, 영향을 미치는 자산 및 함께 그룹화되는 자동화된 수정 작업을 보장하여 중요한 작업에 중점을 두는 것을 포함하여 제품 간 인시던트 검토</span><span class="sxs-lookup"><span data-stu-id="23392-232">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="23392-233">Microsoft 365 Defender가 자동 자동 복구를 통해 손상될 수 있는 자산, 사용자, 장치 및 사서함에 대한 조사를 오케스트레이션하는 방법을 시연합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-233">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="23392-234">고객이 여러 데이터 집합에서 전자 메일, 데이터, 장치 및 계정에 영향을 주는 침입 시도 및 위반 활동을 사전 예방적으로 헌팅하는 방법을 설명하고 예제를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-234">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="23392-235">고객에게 Microsoft 보안 점수를 사용하여 전체적으로 보안 자세를 검토하고 개선할 수 있는 방법을 보여 넣습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-235">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="23392-236"><strong>다음은 범위를 벗어나는 예제입니다.</strong></span><span class="sxs-lookup"><span data-stu-id="23392-236"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="23392-237">고객의 수정 활동에 대한 프로젝트 관리.</span><span class="sxs-lookup"><span data-stu-id="23392-237">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="23392-238">지속적인 관리, 위협 대응 및 수정.</span><span class="sxs-lookup"><span data-stu-id="23392-238">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="23392-239">배포 지침 또는 교육:</span><span class="sxs-lookup"><span data-stu-id="23392-239">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="23392-240">다양한 경고 유형 및 모니터링된 활동을 수정하거나 해석하는 방법</span><span class="sxs-lookup"><span data-stu-id="23392-240">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="23392-241">사용자, 컴퓨터, 측면 이동 경로 또는 엔터티를 조사하는 방법</span><span class="sxs-lookup"><span data-stu-id="23392-241">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="23392-242">사용자 지정 위협 헌팅.</span><span class="sxs-lookup"><span data-stu-id="23392-242">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="23392-243">SIEM(보안 정보 및 이벤트 관리) 또는 API 통합</span><span class="sxs-lookup"><span data-stu-id="23392-243">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23392-244"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="23392-244"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="23392-245">Microsoft Cloud App Security는 모든 Microsoft 및 타사 클라우드 서비스에서 사이버 위협을 식별하고 퇴치하기 위한 풍부한 가시성, 데이터 이동 제어 및 정교한 분석을 제공하는 CASB(Cloud Access Security Broker)입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-245">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="23392-246">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-246">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-247">다음을 포함하여 포털 구성</span><span class="sxs-lookup"><span data-stu-id="23392-247">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="23392-248">사용자 그룹 가져오기.</span><span class="sxs-lookup"><span data-stu-id="23392-248">Importing user groups.</span></span></li>
<li> <span data-ttu-id="23392-249">관리자 액세스 및 설정 관리</span><span class="sxs-lookup"><span data-stu-id="23392-249">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="23392-250">배포를 구성하여 모니터링하거나 모니터링에서 제외할 특정 사용자 그룹을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-250">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="23392-251">IP 범위 및 태그 설정</span><span class="sxs-lookup"><span data-stu-id="23392-251">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="23392-252">로고 및 사용자 지정 메시징을 사용하여 최종 사용자 환경을 개인 설정</span><span class="sxs-lookup"><span data-stu-id="23392-252">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="23392-253">클라우드 검색을 설정하여 섀도 IT를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-253">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="23392-254">끝점용 Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="23392-254">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="23392-255">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="23392-255">Zscaler.</span></span></li>
<li> <span data-ttu-id="23392-256">iboss.</span><span class="sxs-lookup"><span data-stu-id="23392-256">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="23392-257">앱 <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">커넥터를 사용하여</a> 주요 앱을 연결합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-257">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="23392-258">조건부 액세스 및 Cloud App Security 포털에서 조건부 액세스 앱 컨트롤을 설정하여 실시간 세션 컨트롤을 적용합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-258">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="23392-259">Cloud App Security 및 클라우드 검색 대시보드 배포</span><span class="sxs-lookup"><span data-stu-id="23392-259">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="23392-260">조직의 우선 순위에 따라 앱 위험 점수를 사용자 지정합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-260">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="23392-261">앱 태그 및 범주 만들기</span><span class="sxs-lookup"><span data-stu-id="23392-261">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="23392-262">앱에 대한 인가 및 비이용성.</span><span class="sxs-lookup"><span data-stu-id="23392-262">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="23392-263">활동 및 파일 로그 사용</span><span class="sxs-lookup"><span data-stu-id="23392-263">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="23392-264">OAuth 앱 관리</span><span class="sxs-lookup"><span data-stu-id="23392-264">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="23392-265">Microsoft 365 Defender 포털의 인시던트 상관 관계 이해</span><span class="sxs-lookup"><span data-stu-id="23392-265">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="23392-266">CASB의 상위 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20개</a> 사용 사례(다음을 제외한 최대 6개의 정책 생성 또는 업데이트 포함)에 대한 구성 지원을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-266">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="23392-267">IaaS(인터넷 as a Service) 환경의 구성 감사(#18.</span><span class="sxs-lookup"><span data-stu-id="23392-267">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="23392-268">IaaS 환경에서 위협으로부터 보호하기 위한 사용자 활동 모니터링(#19.</span><span class="sxs-lookup"><span data-stu-id="23392-268">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="23392-269"><strong>다음은 범위를 벗어나는 예제입니다.</strong></span><span class="sxs-lookup"><span data-stu-id="23392-269"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="23392-270">고객의 수정 활동에 대한 프로젝트 관리.</span><span class="sxs-lookup"><span data-stu-id="23392-270">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="23392-271">지속적인 관리, 위협 대응 및 수정.</span><span class="sxs-lookup"><span data-stu-id="23392-271">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="23392-272">Docker 또는 로그 수집기를 사용하여 연속 보고서에 대한 자동 로그 업로드 인프라, 설치 또는 배포 설정</span><span class="sxs-lookup"><span data-stu-id="23392-272">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="23392-273">자세한 내용은 CASB에 대한 상위 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20개</a> 사용 사례를 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-273">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="23392-274">클라우드 검색 스냅숏 보고서 만들기</span><span class="sxs-lookup"><span data-stu-id="23392-274">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="23392-275">블록 스크립트를 사용하여 앱 사용을 차단합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-275">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="23392-276">사용자 지정 앱 연결.</span><span class="sxs-lookup"><span data-stu-id="23392-276">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="23392-277">타사 ISP(ID 공급자) 및 DLP(데이터 손실 방지) 공급자와 통합</span><span class="sxs-lookup"><span data-stu-id="23392-277">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="23392-278">고급 헌팅에 대한 교육 또는 지침.</span><span class="sxs-lookup"><span data-stu-id="23392-278">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="23392-279">Microsoft Power Automate 플레이북을 포함한 자동화된 조사 및 수정</span><span class="sxs-lookup"><span data-stu-id="23392-279">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="23392-280">SIEM(보안 정보 및 이벤트 관리) 또는 API 통합(Azure Sentinel 포함)</span><span class="sxs-lookup"><span data-stu-id="23392-280">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="23392-281">개념 증명으로 Cloud App Discovery 배포</span><span class="sxs-lookup"><span data-stu-id="23392-281">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="23392-282"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="23392-282"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="23392-283">Microsoft Defender Advanced Threat Protection (ATP)는 엔터프라이즈 네트워크가 고급 위협을 방지, 탐지, 조사 및 대응하는 데 도움이 되도록 설계된 플랫폼입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-283">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="23392-284">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-284">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-285">끝점을 보호하는 기술을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-285">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="23392-286">끝점 보호 및 장치 제한 프로필 구성</span><span class="sxs-lookup"><span data-stu-id="23392-286">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="23392-287">OS 버전 및 장치 관리(Intune, Microsoft Endpoint Configuration Manager, GPOS(그룹 정책 개체) 및 타사 구성 포함) 및 Windows Defender AV 서비스 또는 기타 끝점 보안 소프트웨어의 상태를 평가합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-287">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="23392-288">Windows AV 서비스 또는 기타 끝점 보안 소프트웨어의 상태 평가</span><span class="sxs-lookup"><span data-stu-id="23392-288">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="23392-289">네트워크 트래픽을 제한하는 Proxies 및 방화벽 평가</span><span class="sxs-lookup"><span data-stu-id="23392-289">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="23392-290">온보딩 끝점을 사용하여 ATP 에이전트 프로필을 배포하는 방법을 설명하여 Microsoft Defender ATP 서비스를 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="23392-290">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="23392-291">다음에 대한 배포 지침, 구성 지원 및 교육:</span><span class="sxs-lookup"><span data-stu-id="23392-291">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="23392-292">위협 및 취약성 관리.</span><span class="sxs-lookup"><span data-stu-id="23392-292">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-293">공격 표면 감소.</span><span class="sxs-lookup"><span data-stu-id="23392-293">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-294">차세대 보호.</span><span class="sxs-lookup"><span data-stu-id="23392-294">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-295">끝점 감지 및 대응.</span><span class="sxs-lookup"><span data-stu-id="23392-295">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-296">자동화된 조사 및 조치.</span><span class="sxs-lookup"><span data-stu-id="23392-296">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-297">보안 점수.</span><span class="sxs-lookup"><span data-stu-id="23392-297">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="23392-298">시뮬레이션 및 자습서 검토(예: 연습 시나리오, 가짜 맬웨어 및 자동화된 조사).</span><span class="sxs-lookup"><span data-stu-id="23392-298">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="23392-299">보고 및 위협 분석 기능 개요</span><span class="sxs-lookup"><span data-stu-id="23392-299">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="23392-300">Office 365 ATP와 Microsoft Defender ATP 통합.</span><span class="sxs-lookup"><span data-stu-id="23392-300">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="23392-301">Microsoft Defender 보안 센터 포털 탐색.</span><span class="sxs-lookup"><span data-stu-id="23392-301">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="23392-302">다음 운영 체제는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-302">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="23392-303">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="23392-303">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-304">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="23392-304">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-305">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="23392-305">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-306">Windows Server 2019 Core Edition</span><span class="sxs-lookup"><span data-stu-id="23392-306">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-307">Windows Server Semi-Annual 채널(SAC) 버전 1803.</span><span class="sxs-lookup"><span data-stu-id="23392-307">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-308">macOS 버전 10.13, 10.14 및 10.15.</span><span class="sxs-lookup"><span data-stu-id="23392-308">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="23392-309">
<strong>참고:</strong> 모든 Windows Server 버전은 최신 버전의 System Center Configuration Manager 2012(버전 1012 R2, 1511 또는 1602) 또는 Microsoft Endpoint Configuration Manager(버전 2002 이상)에서 관리해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-309">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="23392-310"></li>
</ul>

<strong>다음은 범위를 벗어나는 예제입니다. </strong>  
</span><span class="sxs-lookup"><span data-stu-id="23392-310"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="23392-311">고객의 수정 활동에 대한 프로젝트 관리.</span><span class="sxs-lookup"><span data-stu-id="23392-311">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="23392-312">현장 지원.</span><span class="sxs-lookup"><span data-stu-id="23392-312">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="23392-313">지속적인 관리와 위협 대응.</span><span class="sxs-lookup"><span data-stu-id="23392-313">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="23392-314">다음 Microsoft Defender ATP 에이전트에 대한 온보딩 또는 구성:</span><span class="sxs-lookup"><span data-stu-id="23392-314">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="23392-315">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="23392-315">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-316">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="23392-316">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-317">Linux.</span><span class="sxs-lookup"><span data-stu-id="23392-317">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-318">모바일 장치(Android 및 iOS).</span><span class="sxs-lookup"><span data-stu-id="23392-318">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="23392-319">서버 온보더링 및 구성:</span><span class="sxs-lookup"><span data-stu-id="23392-319">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="23392-320">오프라인 통신을 위한 프록시 서버 구성</span><span class="sxs-lookup"><span data-stu-id="23392-320">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-321">다운 수준 Configuration Manager 인스턴스 및 버전에서 Configuration Manager 배포 패키지 구성</span><span class="sxs-lookup"><span data-stu-id="23392-321">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-322">Azure 보안 센터에 서버 온보더링</span><span class="sxs-lookup"><span data-stu-id="23392-322">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-323">Configuration Manager에서 관리되지 않는 서버입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-323">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="23392-324">macOS 온보더링 및 구성:</span><span class="sxs-lookup"><span data-stu-id="23392-324">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="23392-325">수동 Intune 기반 배포.</span><span class="sxs-lookup"><span data-stu-id="23392-325">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-326">JAMF 기반 배포.</span><span class="sxs-lookup"><span data-stu-id="23392-326">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="23392-327">기타 MDM(모바일 장치 관리) 제품 기반 배포.</span><span class="sxs-lookup"><span data-stu-id="23392-327">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-328">수동 배포.</span><span class="sxs-lookup"><span data-stu-id="23392-328">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="23392-329">다음 공격 표면 감소에 대한 기능:</span><span class="sxs-lookup"><span data-stu-id="23392-329">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="23392-330">하드웨어 기반 격리.</span><span class="sxs-lookup"><span data-stu-id="23392-330">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-331">앱 컨트롤.</span><span class="sxs-lookup"><span data-stu-id="23392-331">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-332">악용 방지.</span><span class="sxs-lookup"><span data-stu-id="23392-332">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-333">네트워크 방화벽.</span><span class="sxs-lookup"><span data-stu-id="23392-333">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="23392-334">Microsoft 위협 전문가 등록 또는 구성.</span><span class="sxs-lookup"><span data-stu-id="23392-334">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="23392-335">API 또는 SIEM(보안 정보 및 이벤트 관리) 연결을 검토하는 구성 또는 교육</span><span class="sxs-lookup"><span data-stu-id="23392-335">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="23392-336">MTP(Microsoft 위협 방지) 등록 또는 구성.</span><span class="sxs-lookup"><span data-stu-id="23392-336">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="23392-337">고급 헌팅에 대한 교육 또는 지침.</span><span class="sxs-lookup"><span data-stu-id="23392-337">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="23392-338">Kusto 쿼리의 사용 또는 생성에 대한 교육 또는 지침입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-338">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="23392-339">Microsoft 파트너에게 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">이러한</a> 서비스에 대한 지원을 요청하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-339">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="23392-340"><strong>Microsoft Defender for Identity </strong></span><span class="sxs-lookup"><span data-stu-id="23392-340"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="23392-341">ID용 Microsoft Defender는 온-프레미스 Active Directory 신호를 활용하여 조직에서 일어나는 고급 위협, ID 손상 및 악의적인 내부자 작업을 식별, 감지 및 조사하는 클라우드 기반 보안 솔루션입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-341">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="23392-342">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-342">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="23392-343">ID용 Defender 인스턴스 만들기</span><span class="sxs-lookup"><span data-stu-id="23392-343">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="23392-344">ID용 Defender를 Active Directory에 연결합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-344">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="23392-345">다음을 포함하여 도메인 컨트롤러에 ID용 Defender 센서를 배포하기 위한 환경의 준비 상태를 평가합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-345">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="23392-346">자원 용량 계획을 위한 크기 조정 도구 실행</span><span class="sxs-lookup"><span data-stu-id="23392-346">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="23392-347">감사 도구를 실행하여 센서와 도메인 컨트롤러의 호환성을 평가합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-347">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="23392-348">다음을 포함하여 도메인 컨트롤러에서 직접 네트워크 트래픽 및 Windows 이벤트를 캡처하고 구문 분석하기 위해 센서를 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-348">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="23392-349">센서 패키지 다운로드.</span><span class="sxs-lookup"><span data-stu-id="23392-349">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="23392-350">센서 구성</span><span class="sxs-lookup"><span data-stu-id="23392-350">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="23392-351">자동으로 도메인 컨트롤러에 센서를 설치합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-351">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="23392-352">다중 포리스트 환경에 센서 배포</span><span class="sxs-lookup"><span data-stu-id="23392-352">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="23392-353">ID용 Defender를 Microsoft Cloud App Security와 통합합니다(Cloud App Security 라이선스가 필요하지 않습니다).</span><span class="sxs-lookup"><span data-stu-id="23392-353">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="23392-354">다음에 대한 배포 지침, 구성 지원 및 교육을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-354">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="23392-355">"노이즈"를 줄이기 위해 환경을 조정합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-355">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="23392-356">ID 보안 환경 평가 보고서 이해</span><span class="sxs-lookup"><span data-stu-id="23392-356">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="23392-357">사용자 조사 우선 순위 점수 및 사용자 조사 순위 보고서 이해</span><span class="sxs-lookup"><span data-stu-id="23392-357">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="23392-358">비활성 사용자 보고서 이해</span><span class="sxs-lookup"><span data-stu-id="23392-358">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="23392-359">손상된 계정에 대한 수정 옵션 제공</span><span class="sxs-lookup"><span data-stu-id="23392-359">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="23392-360">ATA(Advanced Threat Analytics)에서 ID용 Defender로의 마이그레이션을 촉진합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-360">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="23392-361"><strong>다음은 범위를 벗어나는 예제입니다.</strong></span><span class="sxs-lookup"><span data-stu-id="23392-361"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="23392-362">고객의 수정 활동에 대한 프로젝트 관리.</span><span class="sxs-lookup"><span data-stu-id="23392-362">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="23392-363">지속적인 관리, 위협 대응 및 수정.</span><span class="sxs-lookup"><span data-stu-id="23392-363">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="23392-364">다음을 포함하여 ID용 Defender 센서 배포</span><span class="sxs-lookup"><span data-stu-id="23392-364">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="23392-365">수동 용량 계획</span><span class="sxs-lookup"><span data-stu-id="23392-365">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="23392-366">독립 실행형 용량으로 센서 배포</span><span class="sxs-lookup"><span data-stu-id="23392-366">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="23392-367">NIC(Network Interface Card) 팀 어댑터를 사용하여 센서 배포</span><span class="sxs-lookup"><span data-stu-id="23392-367">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="23392-368">타사 도구를 통해 센서 배포.</span><span class="sxs-lookup"><span data-stu-id="23392-368">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="23392-369">웹 프록시 연결을 통해 ID용 Defender 클라우드 서비스에 연결합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-369">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="23392-370">벌집 만들기 및 관리</span><span class="sxs-lookup"><span data-stu-id="23392-370">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="23392-371">배포 지침 또는 교육:</span><span class="sxs-lookup"><span data-stu-id="23392-371">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="23392-372">다양한 경고 유형 및 모니터링된 활동을 수정하거나 해석합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-372">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="23392-373">사용자, 컴퓨터, 측면 이동 경로 또는 엔터티 조사.</span><span class="sxs-lookup"><span data-stu-id="23392-373">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="23392-374">위협 또는 고급 헌팅.</span><span class="sxs-lookup"><span data-stu-id="23392-374">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="23392-375">인시던트 대응.</span><span class="sxs-lookup"><span data-stu-id="23392-375">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="23392-376">ID용 Defender에 대한 보안 경고 랩 자습서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-376">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="23392-377">ID에 대한 Defender가 지명된 센서를 통해 syslog 서버에 보안 알림을 보내 의심스러운 활동을 감지할 때 알림을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-377">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="23392-378">SAMR(보안 계정 관리자 원격) 프로토콜을 사용하여 쿼리를 수행하여 특정 컴퓨터의 로컬 관리자를 식별하도록 ID에 대한 Defender를 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-378">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="23392-379">VPN 연결의 정보를 사용자의 프로필 페이지에 추가하도록 VPN 솔루션을 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-379">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="23392-380">SIEM(보안 정보 및 이벤트 관리) 또는 API 통합(Azure Sentinel 포함)</span><span class="sxs-lookup"><span data-stu-id="23392-380">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="23392-381">개념 증명으로 ID 센서용 Defender 배포</span><span class="sxs-lookup"><span data-stu-id="23392-381">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="23392-382">Active Directory가 배포되었습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-382">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="23392-383">ID용 Defender 센서를 설치하려는 도메인 컨트롤러는 ID용 Defender 클라우드 서비스에 인터넷에 연결되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-383">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="23392-384">ID 클라우드 서비스용 Defender와 통신하려면 방화벽 및 프록시가 열려 있어야 합니다(\*.atp.azure.com 포트 443이 열려 있어야 합니다).</span><span class="sxs-lookup"><span data-stu-id="23392-384">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="23392-385">다음 중 하나에서 실행되는 도메인 컨트롤러:</span><span class="sxs-lookup"><span data-stu-id="23392-385">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="23392-386">Windows Server 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="23392-386">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="23392-387">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="23392-387">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="23392-388">Windows Server 2012 R2</span><span class="sxs-lookup"><span data-stu-id="23392-388">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="23392-389">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="23392-389">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="23392-390">Windows Server 2019 KB4487044(OS 빌드 17763.316)</span><span class="sxs-lookup"><span data-stu-id="23392-390">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><span data-ttu-id="23392-391"><strong>Microsoft 정보 거버넌스</strong></span><span class="sxs-lookup"><span data-stu-id="23392-391"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="23392-392">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-392">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-393">보존 레이블 및 정책.</span><span class="sxs-lookup"><span data-stu-id="23392-393">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="23392-394">레코드 관리.</span><span class="sxs-lookup"><span data-stu-id="23392-394">Records management.</span></span>  </li>
<li>  <span data-ttu-id="23392-395">삭제 정책.</span><span class="sxs-lookup"><span data-stu-id="23392-395">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="23392-396">커뮤니케이션 규정 준수.</span><span class="sxs-lookup"><span data-stu-id="23392-396">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="23392-397">참가자 위험 관리.</span><span class="sxs-lookup"><span data-stu-id="23392-397">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="23392-398">Advanced eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="23392-398">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="23392-399">

  <strong>다음은 범위를 벗어나는 예제입니다. </strong>  
</span><span class="sxs-lookup"><span data-stu-id="23392-399">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="23392-400">레코드 관리 파일 계획 개발</span><span class="sxs-lookup"><span data-stu-id="23392-400">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="23392-401">데이터 커넥터</span><span class="sxs-lookup"><span data-stu-id="23392-401">Data connectors.</span></span></li>
<li> <span data-ttu-id="23392-402">정보 장벽.</span><span class="sxs-lookup"><span data-stu-id="23392-402">Information barriers.</span></span></li>
<li> <span data-ttu-id="23392-403">권한이 부여된 액세스 관리.</span><span class="sxs-lookup"><span data-stu-id="23392-403">Privileged access management.</span></span></li>
<li> <span data-ttu-id="23392-404">SharePoint의 정보 아키텍처 개발.</span><span class="sxs-lookup"><span data-stu-id="23392-404">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="23392-405">사용자 지정 스크립팅 및 코딩.</span><span class="sxs-lookup"><span data-stu-id="23392-405">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="23392-406">일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 최소 시스템 요구 사항은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-406">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23392-407"><strong>Microsoft Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="23392-407"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="23392-408">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-408">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-409">데이터 분류.</span><span class="sxs-lookup"><span data-stu-id="23392-409">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="23392-410">민감 정보 유형</span><span class="sxs-lookup"><span data-stu-id="23392-410">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="23392-411">민감도 레이블의 만들기</span><span class="sxs-lookup"><span data-stu-id="23392-411">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="23392-412">민감도 레이블 적용</span><span class="sxs-lookup"><span data-stu-id="23392-412">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="23392-413">통합 레이블 구성</span><span class="sxs-lookup"><span data-stu-id="23392-413">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="23392-414">교육 가능한 분류자</span><span class="sxs-lookup"><span data-stu-id="23392-414">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="23392-415">콘텐츠 탐색기와 활동 탐색기를 사용하여 데이터 확인</span><span class="sxs-lookup"><span data-stu-id="23392-415">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="23392-416">정책을 사용하여 레이블 게시(수동 및 자동)</span><span class="sxs-lookup"><span data-stu-id="23392-416">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="23392-417">Microsoft Teams 채팅 및 채널에 대한 DLP(데이터 손실 방지) 정책 생성.</span><span class="sxs-lookup"><span data-stu-id="23392-417">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="23392-418">Windows 10 장치에 대한 끝점 DLP 정책 만들기</span><span class="sxs-lookup"><span data-stu-id="23392-418">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="23392-419">

<strong>다음은 범위를 벗어나는 예제입니다. </strong>  
</span><span class="sxs-lookup"><span data-stu-id="23392-419">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="23392-420">고객 키.</span><span class="sxs-lookup"><span data-stu-id="23392-420">Customer key.</span></span></li>
<li><span data-ttu-id="23392-421">중요한 정보 유형에 대한 사용자 지정 정규식(RegEx) 개발</span><span class="sxs-lookup"><span data-stu-id="23392-421">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="23392-422">키워드 사전 만들기 또는 수정</span><span class="sxs-lookup"><span data-stu-id="23392-422">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="23392-423">사용자 지정 스크립팅 및 코딩.</span><span class="sxs-lookup"><span data-stu-id="23392-423">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="23392-424">
<strong>참고:</strong> 자세한 내용은 Enterprise Mobility + Security의 <strong>Azure Information Protection을</strong> <a href="#enterprise-mobility--security">참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="23392-424">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="23392-425">일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 최소 시스템 요구 사항은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-425">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="23392-426"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="23392-426"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="23392-427">앱 및 장치에 대한 클라우드 기반 MDM(모바일 장치 관리) 및 MAM(모바일 앱 관리) 공급자로 Intune을 사용할 준비를 위한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-427">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="23392-428">정확한 단계는 원본 환경에 따라 다르며 모바일 장치와 모바일 앱 관리 요구 사항에 기반합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-428">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="23392-429">해당 단계는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-429">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="23392-430">최종 사용자에게 라이선스 부여</span><span class="sxs-lookup"><span data-stu-id="23392-430">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="23392-431">Intune에서 사용할 ID를 구성하는 데 사용할 ID는 Azure AD(클라우드 ID)를 활용합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-431">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="23392-432">Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기</span><span class="sxs-lookup"><span data-stu-id="23392-432">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="23392-433">다음을 비롯한 관리 요구에 따라 MDM 기관 구성</span><span class="sxs-lookup"><span data-stu-id="23392-433">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="23392-434">Intune이 유일한 MDM 솔루션인 경우 Intune을 MDM 기관으로 설정</span><span class="sxs-lookup"><span data-stu-id="23392-434">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="23392-435">MDM 지침 제공:</span><span class="sxs-lookup"><span data-stu-id="23392-435">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-436">MDM 관리 정책의 유효성을 검사하는 데 사용할 테스트 그룹 구성</span><span class="sxs-lookup"><span data-stu-id="23392-436">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="23392-437">다음과 같은 MDM 관리 정책 및 서비스 구성</span><span class="sxs-lookup"><span data-stu-id="23392-437">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="23392-438">웹 링크 또는 딥 링크를 통해 지원되는 각 플랫폼에 대한 앱 배포.</span><span class="sxs-lookup"><span data-stu-id="23392-438">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="23392-439">조건부 액세스 정책</span><span class="sxs-lookup"><span data-stu-id="23392-439">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="23392-440">조직에 기존 인증 기관, 무선 네트워크 또는 VPN 인프라가 있는 경우 전자 메일, 무선 네트워크 및 VPN 프로필 배포.</span><span class="sxs-lookup"><span data-stu-id="23392-440">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="23392-441">Intune 데이터 웨어하우스에 연결</span><span class="sxs-lookup"><span data-stu-id="23392-441">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="23392-442">다음에 Intune 통합:</span><span class="sxs-lookup"><span data-stu-id="23392-442">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="23392-443">원격 지원을 위한 팀 뷰어(팀 뷰어 구독 필요)</span><span class="sxs-lookup"><span data-stu-id="23392-443">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="23392-444">MTD(Mobile Threat Defense) 파트너 솔루션(MTD 구독이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-444">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="23392-445">통신 비용 관리 솔루션(통신 비용 관리 솔루션 구독 필요)</span><span class="sxs-lookup"><span data-stu-id="23392-445">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="23392-446">각 지원되는 플랫폼의 장치를 Intune에 등록합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-446">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="23392-447">앱 보호 지침 제공:</span><span class="sxs-lookup"><span data-stu-id="23392-447">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="23392-448">지원되는 각 플랫폼에 대한 Intune 앱 보호 정책 구성</span><span class="sxs-lookup"><span data-stu-id="23392-448">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="23392-449">관리되는 앱에 대한 조건부 액세스 정책 구성</span><span class="sxs-lookup"><span data-stu-id="23392-449">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="23392-450">앞서 언급한 MAM 정책을 통해 적절한 사용자 그룹을 대상으로 지정합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-450">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="23392-451">관리되는 앱 사용 현황 보고서 사용.</span><span class="sxs-lookup"><span data-stu-id="23392-451">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="23392-452">레거시 PC 관리에서 Intune MDM으로의 마이그레이션 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-452">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="23392-453">
 
</li>
</ul>
  
<strong>클라우드 연결</strong></span><span class="sxs-lookup"><span data-stu-id="23392-453">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="23392-454">Intune을 통해 기존 Configuration Manager 환경을 클라우드에 연결할 수 있는 준비를 안내합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-454">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="23392-455">정확한 단계는 원본 환경에 따라 다릅니다.</span><span class="sxs-lookup"><span data-stu-id="23392-455">The exact steps depend on your source environment.</span></span> <span data-ttu-id="23392-456">해당 단계는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-456">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="23392-457">최종 사용자에게 라이선스 부여</span><span class="sxs-lookup"><span data-stu-id="23392-457">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="23392-458">온-프레미스 Active Directory 및 클라우드 ID를 활용하여 Intune에서 사용할 ID 구성</span><span class="sxs-lookup"><span data-stu-id="23392-458">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="23392-459">Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기</span><span class="sxs-lookup"><span data-stu-id="23392-459">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="23392-460">하이브리드 Azure AD 가입을 설정하는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-460">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="23392-461">MDM 자동 등록을 위해 Azure AD를 설정하는 방법에 대한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-461">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="23392-462">원격 인터넷 기반 장치 관리를 공동 관리하기 위한 솔루션으로 사용될 때 클라우드 관리 게이트웨이를 설정하는 방법에 대한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-462">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="23392-463">Intune으로 전환할 지원되는 작업 부하를 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-463">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="23392-464">Intune에서 등록된 디바이스에서 Configuration Manager 클라이언트를 설치합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-464">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="23392-465"><strong>iOS 및 Android용 Outlook 모바일을 안전하게 배포</strong> 조직에서 iOS 및 Android용 Outlook 모바일을 안전하게 배포하여 사용자가 필요한 모든 앱을 설치하도록 하는 데 도움이 되는 지침을 제공할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-465"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="23392-466">Intune을 통해 iOS 및 Android용 Outlook 모바일을 안전하게 배포하는 단계는 원본 환경에 따라 다를 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-466">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="23392-467">여기에는 다음이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-467">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="23392-468">Apple App Store 또는 Google Play 스토어를 통해 iOS 및 Android용 Outlook, Microsoft Authenticator 및 Intune 회사 포털 앱을 다운로드합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-468">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="23392-469">설정에 대한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-469">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="23392-470">Intune을 사용하여 iOS 및 Android용 Outlook, Microsoft Authenticator 및 Intune 회사 포털 앱을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-470">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="23392-471">앱 보호 정책.</span><span class="sxs-lookup"><span data-stu-id="23392-471">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="23392-472">조건부 액세스 정책</span><span class="sxs-lookup"><span data-stu-id="23392-472">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="23392-473">앱 구성 정책.</span><span class="sxs-lookup"><span data-stu-id="23392-473">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="23392-474">IT 관리자는 Intune을 사용하여 무선 네트워크 및 VPN 프로필 배포를 계획할 때 기존 인증 기관, 무선 네트워크 및 VPN 인프라가 프로덕션 환경에서 이미 작동해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-474">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="23392-475"><strong>참고:</strong>FastTrack 서비스 혜택에는 Intune에 대한 인증 기관, 무선 네트워크, VPN 인프라 또는 Apple MDM 푸시 인증서를 설정하거나 구성하기 위한 지원이 포함되어서는 안 됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-475"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="23392-476"><strong>참고</strong>: 클라우드 연결 기능을 지원하는 데 필요한 최소 요구 사항에 맞게 Configuration Manager 사이트 서버 또는 Configuration Manager 클라이언트를 설정하거나 업그레이드하기 위한 지원은 FastTrack 서비스 혜택에 포함되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-476"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="23392-477">이에 대한 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">지원은 Microsoft 파트너에게</a> 문의하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-477">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="23392-478"><strong>Microsoft Defender ATP(Advanced Threat Protection)에 통합된 Intune</strong></span><span class="sxs-lookup"><span data-stu-id="23392-478"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="23392-479"><strong>참고:</strong>Microsoft Defender ATP와 Intune을 통합하고 Windows 10 위험 수준 평가를 기반으로 장치 준수 정책을 만드는 데 도움을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-479"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="23392-480">구매, 라이선스 또는 정품 인증에 대한 지원은 제공하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-480">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="23392-481">이에 대한 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">지원은 Microsoft 파트너에게</a> 문의하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-481">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="23392-482"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="23392-482"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="23392-483">IT 관리자는 하드웨어 공급 업체가 사용자를 대신하여 하드웨어 ID를 업로드하거나 Windows Autopilot 서비스로 업로드하는 방법으로 조직에 장치를 등록합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-483">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>

<tr class="odd">
<td><span data-ttu-id="23392-484"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="23392-484"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="23392-485">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-485">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-486">안전한 링크, 안전한 첨부 파일 및 피싱 방지 사용.</span><span class="sxs-lookup"><span data-stu-id="23392-486">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="23392-487">자동화, 조사 및 대응 구성.</span><span class="sxs-lookup"><span data-stu-id="23392-487">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="23392-488">공격 시뮬레이터 사용.</span><span class="sxs-lookup"><span data-stu-id="23392-488">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="23392-489">보고 및 위협 분석.</span><span class="sxs-lookup"><span data-stu-id="23392-489">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="23392-490">일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 최소 시스템 요구 사항은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-490">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="23392-491">Office 365</span><span class="sxs-lookup"><span data-stu-id="23392-491">Office 365</span></span>

<<table>
<thead>
<tr class="header">
<th><span data-ttu-id="23392-492"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="23392-492"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="23392-493"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="23392-493"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="23392-494"><strong>원본 환경 기대치</strong></span><span class="sxs-lookup"><span data-stu-id="23392-494"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="23392-495"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="23392-495"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="23392-496">Exchange Online의 경우 조직에서 전자 메일을 사용할 수 있도록 준비하는 프로세스를 안내합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-496">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="23392-497">정확한 단계는 원본 환경 및 전자 메일 마이그레이션 계획에 따라 다를 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-497">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="23392-498">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-498">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-499">Office 365에서 유효성이 검사된 모든 메일 사용이 가능한 도메인에 대해 EOP(Exchange Online Protection) 기능을 설정합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-499">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="23392-500">MX(메일 교환) 레코드를 Office 365로 설정</span><span class="sxs-lookup"><span data-stu-id="23392-500">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="23392-501">구독 서비스의 일부인 경우 Office 365 ATP 기능 설정</span><span class="sxs-lookup"><span data-stu-id="23392-501">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="23392-502">자세한 내용은 이 표의 <strong>Office 365 Advanced Threat Protection</strong> 부분을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-502">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="23392-p126">구독 서비스의 일부로 Office 365에서 확인된 모든 메일 사용 가능 도메인에 대한 데이터 손실 방지(DLP) 기능 설정. MX 레코드가 Office 365를 가리키면 완료됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-p126">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="23392-p127">구독 서비스의 일부로 Office 365에서 확인된 모든 메일 사용 가능 도메인에 대해 Office 365 메시지 암호화(OME)를 설정합니다. MX 레코드가 Office 365를 가리키면 완료됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-p127">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="23392-507">
  <strong>참고:</strong> MRS(사서함 복제 서비스)가 IRM(정보 권한 관리) 전자 메일을 해당 Exchange Online 사서함으로 마이그레이션하려고 합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-507">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="23392-508">마이그레이션 후 보호된 콘텐츠를 읽는 기능은 클라이언트가 AD RMS(Active Directory Rights Managed Services) 서식 파일을 Azure RMS(Azure Rights Management Service)에 매핑하고 복사하는 방법에 따라 다릅니다.</span><span class="sxs-lookup"><span data-stu-id="23392-508">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="23392-509">방화벽 포트 구성</span><span class="sxs-lookup"><span data-stu-id="23392-509">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="23392-510">필요한 자동 검색, SPF(보낸 사람 정책 프레임워크), 도메인 키 식별 메일(DKIM), 도메인 기반 메시지 인증, 보고 및 적합성(DMARC) 및 MX 레코드(필요한 경우)를 비롯한 DNS 설정</span><span class="sxs-lookup"><span data-stu-id="23392-510">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="23392-511">원본 메시징 환경과 Exchange Online 간 전자 메일 흐름 설정(필요한 경우)</span><span class="sxs-lookup"><span data-stu-id="23392-511">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="23392-512">원본 메시징 환경에서 Office 365로 메일 마이그레이션 수행</span><span class="sxs-lookup"><span data-stu-id="23392-512">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="23392-513">사서함 클라이언트(Windows용 Outlook, 웹용 Outlook, iOS 및 Android용 Outlook) 구성</span><span class="sxs-lookup"><span data-stu-id="23392-513">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="23392-514">
  <strong>데이터 마이그레이션</strong>  </span><span class="sxs-lookup"><span data-stu-id="23392-514">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="23392-515">Office 365로의 데이터 마이그레이션에 FastTrack 혜택 사용에 대한 자세한 내용은 데이터 <a href="https://docs.microsoft.com/fasttrack/data-migration">마이그레이션을 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="23392-515">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="23392-516">원본 환경에는 다음 최소 수준 중 하나만 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-516">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="23392-517">Exchange Server 2003 이후 버전을 사용하는 단일 또는 다중 Exchange 조직</span><span class="sxs-lookup"><span data-stu-id="23392-517">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="23392-518">단일 IMAP(Internet Message Access Protocol) 지원 전자 메일 환경</span><span class="sxs-lookup"><span data-stu-id="23392-518">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="23392-519">단일 G 제품군 환경(Gmail, 연락처 및 캘린더만)</span><span class="sxs-lookup"><span data-stu-id="23392-519">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="23392-520">Multi-Geo 기능에 대한 자세한 내용은 <a href="https://go.microsoft.com/fwlink/?linkid=872776">Exchange Online의 Multi-Geo 기능을 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="23392-520">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="23392-521">Project for Office 365, Windows용 Outlook, iOS 및 Android용 Outlook, 비즈니스용 OneDrive 동기화 클라이언트, Power BI Desktop 및 비즈니스용 Skype와 같은 온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office의</a>시스템 요구 사항에 정의된 최소 수준에 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-521">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="23392-522"><strong>Microsoft 정보 거버넌스</strong></span><span class="sxs-lookup"><span data-stu-id="23392-522"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="23392-523">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-523">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-524">보존 레이블 및 정책.</span><span class="sxs-lookup"><span data-stu-id="23392-524">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="23392-525">레코드 관리.</span><span class="sxs-lookup"><span data-stu-id="23392-525">Records management.</span></span>  </li>
<li>  <span data-ttu-id="23392-526">삭제 정책.</span><span class="sxs-lookup"><span data-stu-id="23392-526">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="23392-527">커뮤니케이션 규정 준수.</span><span class="sxs-lookup"><span data-stu-id="23392-527">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="23392-528">참가자 위험 관리.</span><span class="sxs-lookup"><span data-stu-id="23392-528">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="23392-529">Advanced eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="23392-529">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="23392-530">

  <strong>다음은 범위를 벗어나는 예제입니다. </strong>  
</span><span class="sxs-lookup"><span data-stu-id="23392-530">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="23392-531">레코드 관리 파일 계획 개발</span><span class="sxs-lookup"><span data-stu-id="23392-531">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="23392-532">데이터 커넥터</span><span class="sxs-lookup"><span data-stu-id="23392-532">Data connectors.</span></span></li>
<li> <span data-ttu-id="23392-533">정보 장벽.</span><span class="sxs-lookup"><span data-stu-id="23392-533">Information barriers.</span></span></li>
<li> <span data-ttu-id="23392-534">권한이 부여된 액세스 관리.</span><span class="sxs-lookup"><span data-stu-id="23392-534">Privileged access management.</span></span></li>
<li> <span data-ttu-id="23392-535">SharePoint의 정보 아키텍처 개발.</span><span class="sxs-lookup"><span data-stu-id="23392-535">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="23392-536">사용자 지정 스크립팅 및 코딩.</span><span class="sxs-lookup"><span data-stu-id="23392-536">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="23392-537">일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 최소 시스템 요구 사항은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-537">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23392-538"><strong>Microsoft Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="23392-538"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="23392-539">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-539">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-540">데이터 분류.</span><span class="sxs-lookup"><span data-stu-id="23392-540">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="23392-541">민감 정보 유형</span><span class="sxs-lookup"><span data-stu-id="23392-541">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="23392-542">민감도 레이블의 만들기</span><span class="sxs-lookup"><span data-stu-id="23392-542">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="23392-543">민감도 레이블 적용</span><span class="sxs-lookup"><span data-stu-id="23392-543">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="23392-544">통합 레이블 구성</span><span class="sxs-lookup"><span data-stu-id="23392-544">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="23392-545">교육 가능한 분류자</span><span class="sxs-lookup"><span data-stu-id="23392-545">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="23392-546">콘텐츠 탐색기와 활동 탐색기를 사용하여 데이터 확인</span><span class="sxs-lookup"><span data-stu-id="23392-546">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="23392-547">정책을 사용하여 레이블 게시(수동 및 자동)</span><span class="sxs-lookup"><span data-stu-id="23392-547">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="23392-548">Microsoft Teams 채팅 및 채널에 대한 DLP(데이터 손실 방지) 정책 생성.</span><span class="sxs-lookup"><span data-stu-id="23392-548">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="23392-549">Windows 10 장치에 대한 끝점 DLP 정책 만들기</span><span class="sxs-lookup"><span data-stu-id="23392-549">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="23392-550">

<strong>다음은 범위를 벗어나는 예제입니다. </strong>  
</span><span class="sxs-lookup"><span data-stu-id="23392-550">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="23392-551">고객 키.</span><span class="sxs-lookup"><span data-stu-id="23392-551">Customer key.</span></span></li>
<li><span data-ttu-id="23392-552">중요한 정보 유형에 대한 사용자 지정 정규식(RegEx) 개발</span><span class="sxs-lookup"><span data-stu-id="23392-552">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="23392-553">키워드 사전 만들기 또는 수정</span><span class="sxs-lookup"><span data-stu-id="23392-553">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="23392-554">사용자 지정 스크립팅 및 코딩.</span><span class="sxs-lookup"><span data-stu-id="23392-554">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="23392-555">
<strong>참고:</strong> 자세한 내용은 Enterprise Mobility + Security의 <strong>Azure Information Protection을</strong> <a href="#enterprise-mobility--security">참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="23392-555">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="23392-556">일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 최소 시스템 요구 사항은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-556">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23392-557"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="23392-557"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="23392-558">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-558">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-559">Teams를 지원하기 위한 Exchange Online, SharePoint Online, Office 365 그룹 및 Azure AD의 최소 요구 사항 확인</span><span class="sxs-lookup"><span data-stu-id="23392-559">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="23392-560">방화벽 포트 구성</span><span class="sxs-lookup"><span data-stu-id="23392-560">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="23392-561">DNS 설정.</span><span class="sxs-lookup"><span data-stu-id="23392-561">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="23392-562">Office 365 테넌트에서 팀 확인이 가능합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-562">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="23392-563">사용자 라이선스 사용 또는 사용 안 함.</span><span class="sxs-lookup"><span data-stu-id="23392-563">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="23392-564">Teams에 대한 네트워크 평가:</span><span class="sxs-lookup"><span data-stu-id="23392-564">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="23392-565">포트 및 끝점 검사</span><span class="sxs-lookup"><span data-stu-id="23392-565">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="23392-566">연결 품질 검사</span><span class="sxs-lookup"><span data-stu-id="23392-566">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="23392-567">대역폭 예상</span><span class="sxs-lookup"><span data-stu-id="23392-567">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="23392-568">Teams 앱 정책 구성(Teams 웹 앱, Teams 데스크톱 앱 및 iOS 및 Android 앱용 Teams)</span><span class="sxs-lookup"><span data-stu-id="23392-568">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="23392-569">해당하는 경우 다음에 대한 지침도 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-569">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-570">Microsoft Teams 룸 디바이스:</span><span class="sxs-lookup"><span data-stu-id="23392-570">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="23392-571"><a href="https://go.microsoft.com/fwlink/?linkid=2066478">팀 장치 카탈로그</a>에 나열된 지원되는 전화 및 회의실 디바이스에 필요한 온라인 계정 생성.</span><span class="sxs-lookup"><span data-stu-id="23392-571">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="23392-572">인증된 Microsoft Teams 룸 장치의 서비스 쪽 구성에 대한 원격 지원.</span><span class="sxs-lookup"><span data-stu-id="23392-572">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="23392-573">오디오 회의 사용:</span><span class="sxs-lookup"><span data-stu-id="23392-573">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="23392-574">회의 브리지 기본 설정에 대한 조직 설정</span><span class="sxs-lookup"><span data-stu-id="23392-574">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="23392-575">회의 브리지를 라이선스가 있는 사용자에게 할당</span><span class="sxs-lookup"><span data-stu-id="23392-575">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="23392-576">전화 시스템:</span><span class="sxs-lookup"><span data-stu-id="23392-576">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="23392-577">클라우드 음성 기본 설정에 대한 조직 설정</span><span class="sxs-lookup"><span data-stu-id="23392-577">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="23392-578">통화 플랜<a href="https://go.microsoft.com/fwlink/?linkid=2066478">지침(사용 가능한 시장):</a></span><span class="sxs-lookup"><span data-stu-id="23392-578">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="23392-579">라이선스가 있는 사용자에게 번호 할당</span><span class="sxs-lookup"><span data-stu-id="23392-579">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="23392-580">UI(사용자 인터페이스)를 통해 최대 999개의 지역 번호 이식 지침</span><span class="sxs-lookup"><span data-stu-id="23392-580">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="23392-581">999개가 넘는 번호를 지원하는 지역 번호 이식 SR(서비스 요청)</span><span class="sxs-lookup"><span data-stu-id="23392-581">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="23392-582">직접 라우팅 지침:</span><span class="sxs-lookup"><span data-stu-id="23392-582">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="23392-583">파트너 호스팅 시나리오의 직접 라우팅 디자인 또는 최대 10개 사이트에 대한 고객 배포 시나리오에 대한 조직 설정 지침입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-583">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="23392-584">SBC(Session Border Controller) 구성 검토.</span><span class="sxs-lookup"><span data-stu-id="23392-584">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="23392-585">다이얼 플랜 구성에 대한 원격 지원.</span><span class="sxs-lookup"><span data-stu-id="23392-585">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="23392-586">음성 경로 구성</span><span class="sxs-lookup"><span data-stu-id="23392-586">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="23392-587">미디어 우회 및 로컬 미디어 최적화.</span><span class="sxs-lookup"><span data-stu-id="23392-587">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="23392-588">권한 부여 팀 라이브 이벤트</span><span class="sxs-lookup"><span data-stu-id="23392-588">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="23392-589">조직 설정 및 Microsoft Stream에 통합</span><span class="sxs-lookup"><span data-stu-id="23392-589">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="23392-590">비즈니스용 Skype에서 Teams로의 전환에 대한 지침입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-590">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="23392-591">Office 365용 Azure AD에서 사용하도록 설정된 ID입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-591">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="23392-592">SharePoint Online에 대해 사용하는 사용자.</span><span class="sxs-lookup"><span data-stu-id="23392-592">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="23392-593">Exchange 사서함이 있습니다(Exchange 하이브리드 구성의 온라인 및온-프레미스).</span><span class="sxs-lookup"><span data-stu-id="23392-593">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="23392-594">Office 365 그룹에서 사용되도록 설정됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-594">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="23392-595">
  <strong>참고:</strong> 사용자가 SharePoint Online 라이선스를 할당하고 사용하도록 설정하지 않은 경우 Office 365에 비즈니스용 OneDrive 저장소가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-595">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="23392-596">파일 공유는 채널에서 계속 작동하지만 사용자는 Office 365의 비즈니스용 OneDrive 저장소가 없는 채팅에서 파일을 공유할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-596">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="23392-597">Teams는 SharePoint On-premises를 지원하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-597">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="23392-598">
  <strong>참고:</strong> 모든 사용자가 사서함을 Exchange Online에 두는 것이 가장 좋은 상태입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-598">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="23392-599">사서함이 있는 사용자는 Azure AD Connect를 통해 Office 365 디렉터리에 ID를 동기화해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-599">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="23392-600">이러한 Exchange 하이브리드 고객의 경우 사용자의 사서함이 On-premises인 경우 사용자는 커넥터를 추가하거나 구성할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-600">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="23392-601">Microsoft Teams Windows 및 Mac 데스크톱 클라이언트용 설치 관리자는 <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>에서 다운로드할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-601">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23392-602"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="23392-602"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="23392-603">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-603">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-604">안전한 링크, 안전한 첨부 파일 및 피싱 방지 사용.</span><span class="sxs-lookup"><span data-stu-id="23392-604">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="23392-605">자동화, 조사 및 대응 구성.</span><span class="sxs-lookup"><span data-stu-id="23392-605">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="23392-606">공격 시뮬레이터 사용.</span><span class="sxs-lookup"><span data-stu-id="23392-606">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="23392-607">보고 및 위협 분석.</span><span class="sxs-lookup"><span data-stu-id="23392-607">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="23392-608">일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 최소 시스템 요구 사항은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-608">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23392-609"><strong>iOS 및 Android용 Outlook</strong></span><span class="sxs-lookup"><span data-stu-id="23392-609"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="23392-610">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-610">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-611">Apple App Store를 Google Play에서 iOS 및 Android용 Outlook 다운로드</span><span class="sxs-lookup"><span data-stu-id="23392-611">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="23392-612">계정 구성 및 Exchange Online 사서함 액세스</span><span class="sxs-lookup"><span data-stu-id="23392-612">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="23392-613">Outlook 모바일 보안(자세한 내용은 <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Exchange Online에서 iOS</a> 및 Android용 Outlook 보안 참조).</span><span class="sxs-lookup"><span data-stu-id="23392-613">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="23392-614">Office 365용 Azure AD에서 사용하도록 설정된 ID입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-614">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="23392-615">Exchange Online이 구성되고 라이선스가 할당됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-615">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23392-616"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="23392-616"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="23392-617">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-617">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-618">Power BI 라이선스를 할당합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-618">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="23392-619">Power BI Desktop 앱을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-619">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="23392-620">Power BI Desktop과 같은 온라인 클라이언트 소프트웨어는 Microsoft <a href="https://go.microsoft.com/fwlink/?LinkID=723597">365</a>및 Office의 시스템 요구 사항에 정의된 최소 수준 이상이 되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-620">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23392-621"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="23392-621"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="23392-622">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-622">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-623">Project Online이 사용하는 기본 SharePoint 기능 확인</span><span class="sxs-lookup"><span data-stu-id="23392-623">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="23392-624">테넌트에 Project Online 서비스 추가(사용자에게 구독 추가 포함)</span><span class="sxs-lookup"><span data-stu-id="23392-624">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="23392-625">ERP(Enterprise 자원 그룹) 설정</span><span class="sxs-lookup"><span data-stu-id="23392-625">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="23392-626">첫 번째 프로젝트 만들기</span><span class="sxs-lookup"><span data-stu-id="23392-626">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="23392-627">Project for Office 365와 같은 온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365</a>및 Office에 대한 시스템 요구 사항에 정의된 최소 수준에 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-627">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23392-628"><strong>Project Online Professional 및 Premium</strong></span><span class="sxs-lookup"><span data-stu-id="23392-628"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="23392-629">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-629">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-630">배포 문제 해결</span><span class="sxs-lookup"><span data-stu-id="23392-630">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="23392-631">Microsoft 365 관리 센터 및 Windows PowerShell을 사용하여 최종 사용자 라이선스 할당</span><span class="sxs-lookup"><span data-stu-id="23392-631">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="23392-632">간편 실행을 사용하여 Office 365 포털에서 Project Online 데스크톱 클라이언트 설치</span><span class="sxs-lookup"><span data-stu-id="23392-632">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="23392-633">Office 365 배포 도구를 사용하여 업데이트 설정 구성</span><span class="sxs-lookup"><span data-stu-id="23392-633">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="23392-634">Project Online 데스크톱 클라이언트를 위한 단일 사이트에 배포 서버 설정(Office 365 배포 도구용 configuration.xml 파일을 만드는 지침 포함)</span><span class="sxs-lookup"><span data-stu-id="23392-634">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="23392-635">Project Online 데스크톱 클라이언트을 Project Online Professional 또는 Project Online Premium에 연결합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-635">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="23392-636">Project for Office 365와 같은 온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365</a>및 Office에 대한 시스템 요구 사항에 정의된 최소 수준에 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-636">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23392-637"><strong>SharePoint Online 및 비즈니스용 OneDrive</strong></span><span class="sxs-lookup"><span data-stu-id="23392-637"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="23392-638">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-638">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-639">DNS 설정.</span><span class="sxs-lookup"><span data-stu-id="23392-639">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="23392-640">방화벽 포트 구성</span><span class="sxs-lookup"><span data-stu-id="23392-640">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="23392-641">사용자 및 라이선스 프로비전</span><span class="sxs-lookup"><span data-stu-id="23392-641">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="23392-642">SharePoint Online 관리자에 대해 사이트 만들기를 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="23392-642">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="23392-643">사이트 모음 계획</span><span class="sxs-lookup"><span data-stu-id="23392-643">Planning site collections.</span></span></li>
<li><span data-ttu-id="23392-644">콘텐츠 보호 및 권한 관리</span><span class="sxs-lookup"><span data-stu-id="23392-644">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="23392-645">SharePoint Online 기능 구성</span><span class="sxs-lookup"><span data-stu-id="23392-645">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="23392-646">하이브리드 검색, 하이브리드 사이트, 하이브리드 분류, 콘텐츠 형식, 하이브리드 셀프 서비스 사이트 만들기(SharePoint Server 2013 전용), 확장된 앱 시작 관리자, 하이브리드 비즈니스용 OneDrive, 익스트라넷 사이트 등의 SharePoint 하이브리드 기능을 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-646">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="23392-647">마이그레이션 방식</span><span class="sxs-lookup"><span data-stu-id="23392-647">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="23392-648">SharePoint 버전에 따라 비즈니스용 OneDrive에 대한 추가 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-648">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="23392-649">통합 옵션 식별 및 온라인 프레미스 및 온라인 네트워크 인프라 및 대역폭 검토</span><span class="sxs-lookup"><span data-stu-id="23392-649">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="23392-650">SharePoint Online 2013 SP1 설치(해당되는 경우), 동기화 및 ID 요구 사항을 계획 및 구현하고, 비즈니스용 OneDrive 동기화 클라이언트를 식별합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-650">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="23392-651">모든 사용자(또는 단계적 롤아웃)에 대한 단일 출시 계획 및 구현</span><span class="sxs-lookup"><span data-stu-id="23392-651">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="23392-652">라이선스 할당, 내 사이트 및 개인 문서 라이브러리를 Office 365로 리디렉션(SharePoint Online 2013에 해당), 대상 그룹에 OneDrive 액세스 제어(SharePoint Online 2013에 해당) 설정</span><span class="sxs-lookup"><span data-stu-id="23392-652">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="23392-653">알려진 폴더를 OneDrive로 리디렉션하거나 이동합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-653">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="23392-654">비즈니스용 OneDrive 클라이언트 동기화 배포</span><span class="sxs-lookup"><span data-stu-id="23392-654">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="23392-655">
  <strong>데이터 마이그레이션</strong>  </span><span class="sxs-lookup"><span data-stu-id="23392-655">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="23392-656">Office 365로의 데이터 마이그레이션에 FastTrack 혜택 사용에 대한 자세한 내용은 데이터 <a href="https://docs.microsoft.com/fasttrack/data-migration">마이그레이션을 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="23392-656">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="23392-657"><strong>SharePoint 하이브리드의 경우:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="23392-657"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="23392-658">SharePoint 하이브리드 구성에는 하이브리드 검색, 사이트, 세분화, 콘텐츠 형식, 비즈니스용 OneDrive, 확장된 앱 시작 프로그램, 엑스트라넷 사이트 및 온라인에서 단일 대상 SharePoint Online 환경으로 연결된 셀프 서비스 사이트 만들기 구성이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-658">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="23392-659">
  <strong>참고:</strong> 셀프 서비스 사이트 만들기는 SharePoint 2013을 실행하는 On-프레미스 서버의 범위에 있지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-659">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="23392-660">SharePoint 하이브리드를 사용하도록 설정하려면 다음의 On-premises SharePoint Server 환경, 2013, 2016 또는 2019 중 하나를 설정해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-660">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="23392-661">
  <strong>참고:</strong> SharePoint Server로의 On-premises SharePoint 환경 업그레이드는 범위에 있지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-661">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="23392-662">Microsoft 파트너에게 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">지원을</a> 요청하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-662">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="23392-663">자세한 내용은 SharePoint 하이브리드 기능에 대한 최소 공개 업데이트 <a href="https://go.microsoft.com/fwlink/?linkid=853548">수준을 참조하세요.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="23392-663">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="23392-664">
  <strong>참고:</strong> Multi-Geo 기능에 대한 자세한 내용은 <a href="https://go.microsoft.com/fwlink/?linkid=831056">Office 365의 OneDrive 및 SharePoint Online의 Multi-Geo 기능을 참조하세요.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="23392-664">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="23392-665"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="23392-665"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="23392-666">Yammer Enterprise 서비스를 사용하도록 설정하기 위한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-666">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="23392-667">온라인 클라이언트 소프트웨어는 Microsoft 365 및 Office의 시스템 요구 사항에 정의된 최소 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">수준 이상이 되어야 합니다.</a></span><span class="sxs-lookup"><span data-stu-id="23392-667">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="23392-668">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="23392-668">Enterprise Mobility + Security</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="23392-669"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="23392-669"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="23392-670"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="23392-670"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="23392-671"><strong>원본 환경 기대치</strong></span><span class="sxs-lookup"><span data-stu-id="23392-671"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="23392-672"><strong>Azure AD(Azure Active Directory) 및 Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="23392-672"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="23392-673">다음 시나리오에서 클라우드 ID를 보호하는 데 필요한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-673">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="23392-674">

<strong>보안 기본 인프라</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="23392-674">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="23392-675">Azure MFA(Multi-Factor Authentication)(클라우드 전용), Microsoft Authenticator 앱 및 Azure MFA 및 SSPR(셀프 서비스 암호 재설정)에 대한 결합 등록을 포함하여 ID에 대해 강력한 인증을 구성하고 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="23392-675">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="23392-676">Azure AD Premium이 아닌 고객의 경우 보안 기본값을 사용하여 ID를 보호할 수 있는 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-676">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="23392-677">Azure AD 프리미엄 고객의 경우 조건부 액세스로 ID를 보호할 수 있는 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-677">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="23392-678">Azure AD 암호 보호를 사용하여 취약한 암호의 사용을 감지하고 차단합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-678">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="23392-679">Azure AD 응용 프로그램 프록시를 사용하여 프레미스 웹앱에 대한 원격 액세스 보안</span><span class="sxs-lookup"><span data-stu-id="23392-679">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="23392-680">Azure ID 보호를 사용하여 위험 기반 검색 및 수정을 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="23392-680">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="23392-681">사용자 지정 브랜드가 있는 로고, 텍스트 및 이미지를 포함하여 사용자 지정 로그인 화면 사용</span><span class="sxs-lookup"><span data-stu-id="23392-681">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="23392-682">Azure AD B2B를 사용하여 게스트 사용자와 앱 및 서비스를 안전하게 공유합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-682">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="23392-683">RBAC(역할 기반 액세스 제어) 기본 제공 관리 역할을 사용하여 Office 365 관리자에 대한 액세스를 관리하고 권한 있는 관리자 계정 수를 줄입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-683">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="23392-684">하이브리드 Azure AD 조인 구성</span><span class="sxs-lookup"><span data-stu-id="23392-684">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="23392-685">Azure AD 가입 구성</span><span class="sxs-lookup"><span data-stu-id="23392-685">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="23392-686">
  
<strong>모니터링 및 보고</strong>  
</span><span class="sxs-lookup"><span data-stu-id="23392-686">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="23392-687">Azure AD Connect Health를 사용하여 AD FS, Azure AD Connect 및 도메인 컨트롤러에 대한 원격 모니터링을 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="23392-687">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="23392-688">
  
<strong>거버넌스</strong>  
</span><span class="sxs-lookup"><span data-stu-id="23392-688">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="23392-689">Azure AD 권리 부여 관리를 사용하여 Azure AD ID 및 액세스 수명 주기를 대규모로 관리합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-689">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="23392-690">Azure AD 액세스 검토를 사용하여 Azure AD 그룹 구성원 자격, 엔터프라이즈 앱 액세스 및 역할 할당 관리</span><span class="sxs-lookup"><span data-stu-id="23392-690">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-691">Azure AD 사용 약관 검토</span><span class="sxs-lookup"><span data-stu-id="23392-691">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-692">Azure AD Privileged Identity Management를 사용하여 권한 있는 관리자 계정에 대한 액세스를 관리하고 제어합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-692">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="23392-693">
  
<strong>자동화 및 효율성 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="23392-693">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="23392-694">Azure AD SSPR 사용</span><span class="sxs-lookup"><span data-stu-id="23392-694">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="23392-695">사용자가 Azure AD 셀프 서비스 그룹 관리를 사용하여 자체 클라우드 보안 또는 Office 365 그룹을 만들고 관리할 수 있도록 허용</span><span class="sxs-lookup"><span data-stu-id="23392-695">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="23392-696">Azure AD 위임된 그룹 관리를 사용하여 엔터프라이즈 앱에 대한 위임된 액세스 관리</span><span class="sxs-lookup"><span data-stu-id="23392-696">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="23392-697">Azure AD 동적 그룹을 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="23392-697">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="23392-698">컬렉션을 사용하여 내 앱 포털에서 앱 구성</span><span class="sxs-lookup"><span data-stu-id="23392-698">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="23392-699">Azure AD 및 Azure AD Premium 기능과의 통합을 방지하는 식별된 문제의 수정을 포함하여 Azure AD Premium에 대한 On-premises Active Directory 및 해당 환경이 준비되었습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-699">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="23392-700"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="23392-700"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="23392-701">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-701">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-702">테넌트 활성화 및 구성</span><span class="sxs-lookup"><span data-stu-id="23392-702">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="23392-703">레이블과 정책 만들기 및 설정</span><span class="sxs-lookup"><span data-stu-id="23392-703">Creating and setting up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="23392-704">문서에 정보 보호 적용</span><span class="sxs-lookup"><span data-stu-id="23392-704">Applying information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="23392-705">Azure Information Protection 클라이언트를 사용하여 Windows에서 실행 중인 Office 앱(Word, PowerPoint, Excel, Outlook 등)에서 자동으로 정보 분류 및 레이블 지정</span><span class="sxs-lookup"><span data-stu-id="23392-705">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="23392-706">Azure Information Protection 스캐너를 사용하여 미사용 파일 검색 및 레이블 지정</span><span class="sxs-lookup"><span data-stu-id="23392-706">Discovering and labeling files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="23392-707">Exchange Online 메일 흐름 규칙을 사용하여 전송 중인 전자 메일 모니터링</span><span class="sxs-lookup"><span data-stu-id="23392-707">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="23392-708">Microsoft Azure RMS(권한 관리 서비스), OME(Office 365 메시지 암호화) 및 DLP(데이터 손실 방지)를 사용하여 보호를 적용하려는 경우도 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-708">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="23392-709">고객 선행 요구 사항 책임은 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-709">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="23392-710">검사할 파일 공유 위치 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-710">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="23392-711">승인된 분류 분류입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-711">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="23392-712">키 관리에 대한 규정 제한 또는 요구 사항을 이해합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-712">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="23392-713">Azure AD와 동기화된,프레미스 Active Directory에 대해 만들어진 서비스 계정입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-713">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="23392-714">분류 및 보호를 위해 구성된 레이블입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-714">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="23392-715">Azure Information Protection 스캐너에 대한 모든 선행이 준비됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-715">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="23392-716">자세한 내용은 Azure Information Protection 통합 레이블 지정 스캐너를 설치 및 배포하기 위한 선행 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">구성을 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="23392-716">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="23392-717">사용자 장치가 지원되는 운영 체제를 실행하고 있으며 필수 필수가 설치되어 있는지 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-717">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="23392-718">자세한 내용은 다음을 참조합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-718">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="23392-719"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">관리자 가이드: 사용자를 위한 Azure Information Protection 통합 레이블 지정 클라이언트 설치</a>   </span><span class="sxs-lookup"><span data-stu-id="23392-719"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="23392-720"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">iOS 또는 Android용 Azure Information Protection 앱은 무엇입니까?</a>  </span><span class="sxs-lookup"><span data-stu-id="23392-720"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="23392-721">하이브리드 지원을 위한 AD RMS(Active Directory RMS) 커넥터를 포함하여 Azure RMS 커넥터 및 서버의 설치 및 구성</span><span class="sxs-lookup"><span data-stu-id="23392-721">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="23392-722">배포에 이러한 옵션 중 하나를 필요로 하는 경우 BYOK(Bring Your Own Key), DKE(이중 키 암호화)(통합 레이블 지정 클라이언트만 해당) 또는 HYOK(Own Key)를 설치 및 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-722">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="23392-723"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="23392-723"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="23392-724">앱 및 장치에 대한 클라우드 기반 MDM(모바일 장치 관리) 및 MAM(모바일 앱 관리) 공급자로 Intune을 사용할 준비를 위한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-724">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="23392-725">정확한 단계는 원본 환경에 따라 다르며 모바일 장치와 모바일 앱 관리 요구 사항에 기반합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-725">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="23392-726">해당 단계는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-726">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="23392-727">최종 사용자에게 라이선스 부여</span><span class="sxs-lookup"><span data-stu-id="23392-727">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="23392-728">Intune에서 사용할 ID를 구성하는 데 사용할 ID는 Azure AD(클라우드 ID)를 활용합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-728">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="23392-729">Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기</span><span class="sxs-lookup"><span data-stu-id="23392-729">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="23392-730">다음을 비롯한 관리 요구에 따라 MDM 기관 구성</span><span class="sxs-lookup"><span data-stu-id="23392-730">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="23392-731">Intune이 유일한 MDM 솔루션인 경우 Intune을 MDM 기관으로 설정</span><span class="sxs-lookup"><span data-stu-id="23392-731">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="23392-732">MDM 지침 제공:</span><span class="sxs-lookup"><span data-stu-id="23392-732">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-733">MDM 관리 정책의 유효성을 검사하는 데 사용할 테스트 그룹 구성</span><span class="sxs-lookup"><span data-stu-id="23392-733">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="23392-734">다음과 같은 MDM 관리 정책 및 서비스 구성</span><span class="sxs-lookup"><span data-stu-id="23392-734">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="23392-735">웹 링크 또는 딥 링크를 통해 지원되는 각 플랫폼에 대한 앱 배포.</span><span class="sxs-lookup"><span data-stu-id="23392-735">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="23392-736">조건부 액세스 정책</span><span class="sxs-lookup"><span data-stu-id="23392-736">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="23392-737">조직에 기존 인증 기관, 무선 네트워크 또는 VPN 인프라가 있는 경우 전자 메일, 무선 네트워크 및 VPN 프로필 배포.</span><span class="sxs-lookup"><span data-stu-id="23392-737">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="23392-738">Intune 데이터 웨어하우스에 연결</span><span class="sxs-lookup"><span data-stu-id="23392-738">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="23392-739">다음에 Intune 통합:</span><span class="sxs-lookup"><span data-stu-id="23392-739">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="23392-740">원격 지원을 위한 팀 뷰어(팀 뷰어 구독 필요)</span><span class="sxs-lookup"><span data-stu-id="23392-740">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="23392-741">MTD(Mobile Threat Defense) 파트너 솔루션(MTD 구독이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-741">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="23392-742">통신 비용 관리 솔루션(통신 비용 관리 솔루션 구독 필요)</span><span class="sxs-lookup"><span data-stu-id="23392-742">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="23392-743">각 지원되는 플랫폼의 장치를 Intune에 등록합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-743">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="23392-744">앱 보호 지침 제공:</span><span class="sxs-lookup"><span data-stu-id="23392-744">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="23392-745">지원되는 각 플랫폼에 대한 Intune 앱 보호 정책 구성</span><span class="sxs-lookup"><span data-stu-id="23392-745">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="23392-746">관리되는 앱에 대한 조건부 액세스 정책 구성</span><span class="sxs-lookup"><span data-stu-id="23392-746">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="23392-747">앞서 언급한 MAM 정책을 통해 적절한 사용자 그룹을 대상으로 지정합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-747">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="23392-748">관리되는 앱 사용 현황 보고서 사용.</span><span class="sxs-lookup"><span data-stu-id="23392-748">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="23392-749">레거시 PC 관리에서 Intune MDM으로의 마이그레이션 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-749">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="23392-750">
  
</li>
</ul>
  
<strong>클라우드 연결</strong></span><span class="sxs-lookup"><span data-stu-id="23392-750">
  
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="23392-751">Intune을 통해 기존 Configuration Manager 환경을 클라우드에 연결할 수 있는 준비를 안내합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-751">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="23392-752">정확한 단계는 원본 환경에 따라 다릅니다.</span><span class="sxs-lookup"><span data-stu-id="23392-752">The exact steps depend on your source environment.</span></span> <span data-ttu-id="23392-753">해당 단계는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-753">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="23392-754">최종 사용자에게 라이선스 부여</span><span class="sxs-lookup"><span data-stu-id="23392-754">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="23392-755">온-프레미스 Active Directory 및 클라우드 ID를 활용하여 Intune에서 사용할 ID 구성</span><span class="sxs-lookup"><span data-stu-id="23392-755">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="23392-756">Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기</span><span class="sxs-lookup"><span data-stu-id="23392-756">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="23392-757">하이브리드 Azure AD 가입을 설정하는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-757">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="23392-758">MDM 자동 등록을 위해 Azure AD를 설정하는 방법에 대한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-758">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="23392-759">원격 인터넷 기반 장치 관리를 공동 관리하기 위한 솔루션으로 사용될 때 클라우드 관리 게이트웨이를 설정하는 방법에 대한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-759">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="23392-760">Intune으로 전환할 지원되는 작업 부하를 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-760">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="23392-761">Intune에서 등록된 디바이스에서 Configuration Manager 클라이언트를 설치합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-761">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="23392-762"><strong>iOS 및 Android용 Outlook 모바일을 안전하게 배포</strong> 조직에서 iOS 및 Android용 Outlook 모바일을 안전하게 배포하여 사용자가 필요한 모든 앱을 설치하도록 하는 데 도움이 되는 지침을 제공할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-762"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="23392-763">Intune을 통해 iOS 및 Android용 Outlook 모바일을 안전하게 배포하는 단계는 원본 환경에 따라 다를 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-763">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="23392-764">여기에는 다음이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-764">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="23392-765">Apple App Store 또는 Google Play 스토어를 통해 iOS 및 Android용 Outlook, Microsoft Authenticator 및 Intune 회사 포털 앱을 다운로드합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-765">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="23392-766">설정에 대한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-766">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="23392-767">Intune을 사용하여 iOS 및 Android용 Outlook, Microsoft Authenticator 및 Intune 회사 포털 앱을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-767">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="23392-768">앱 보호 정책.</span><span class="sxs-lookup"><span data-stu-id="23392-768">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="23392-769">조건부 액세스 정책</span><span class="sxs-lookup"><span data-stu-id="23392-769">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="23392-770">앱 구성 정책.</span><span class="sxs-lookup"><span data-stu-id="23392-770">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="23392-771">IT 관리자는 Intune을 사용하여 무선 네트워크 및 VPN 프로필 배포를 계획할 때 기존 인증 기관, 무선 네트워크 및 VPN 인프라가 프로덕션 환경에서 이미 작동해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-771">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="23392-772"><strong>참고:</strong>FastTrack 서비스 혜택에는 Intune에 대한 인증 기관, 무선 네트워크, VPN 인프라 또는 Apple MDM 푸시 인증서를 설정하거나 구성하기 위한 지원이 포함되어서는 안 됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-772"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="23392-773"><strong>참고</strong>: 클라우드 연결 기능을 지원하는 데 필요한 최소 요구 사항에 맞게 Configuration Manager 사이트 서버 또는 Configuration Manager 클라이언트를 설정하거나 업그레이드하기 위한 지원은 FastTrack 서비스 혜택에 포함되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-773"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="23392-774">이에 대한 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">지원은 Microsoft 파트너에게</a> 문의하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-774">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="23392-775"><strong>Microsoft Defender ATP(Advanced Threat Protection)에 통합된 Intune</strong></span><span class="sxs-lookup"><span data-stu-id="23392-775"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="23392-776"><strong>참고:</strong>Microsoft Defender ATP와 Intune을 통합하고 Windows 10 위험 수준 평가를 기반으로 장치 준수 정책을 만드는 데 도움을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-776"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="23392-777">구매, 라이선스 또는 정품 인증에 대한 지원은 제공하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-777">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="23392-778">이에 대한 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">지원은 Microsoft 파트너에게</a> 문의하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-778">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="23392-779"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="23392-779"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="23392-780">IT 관리자는 하드웨어 공급 업체가 사용자를 대신하여 하드웨어 ID를 업로드하거나 Windows Autopilot 서비스로 업로드하는 방법으로 조직에 장치를 등록합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-780">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="23392-781">Windows 10</span><span class="sxs-lookup"><span data-stu-id="23392-781">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="23392-782"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="23392-782"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="23392-783"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="23392-783"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="23392-784"><strong>원본 환경 기대치</strong></span><span class="sxs-lookup"><span data-stu-id="23392-784"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="23392-785"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="23392-785"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="23392-786">Windows 7 Professional 및 Windows 8.1 Professional에서 Windows 10 Enterprise로 업그레이드하기 위한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-786">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="23392-787">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-787">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-788">Windows 10 의도 이해</span><span class="sxs-lookup"><span data-stu-id="23392-788">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="23392-789">원본 환경 및 요구 사항 평가(Windows 10 배포를 지원하기 위해 Microsoft Endpoint Configuration Manager를 필요한 수준으로 업그레이드해야 합니다).</span><span class="sxs-lookup"><span data-stu-id="23392-789">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="23392-790">Microsoft Endpoint Configuration Manager 또는 Microsoft 365를 사용하여 Windows 10 Enterprise 및 Microsoft 365 앱을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-790">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="23392-791">Windows 10 앱을 평가할 수 있는 권장 옵션입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-791">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="23392-792">Desktop Analytics 배포 계획 생성을 통해 Desktop Analytics 및 지침을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-792">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="23392-793">Configuration Manager에서 Office 365 준비 대시보드를 활용하거나 Office용 독립 실행형 준비 Toolkit Microsoft 365 앱 배포를 지원하여 Microsoft 365 앱 호환성 평가.</span><span class="sxs-lookup"><span data-stu-id="23392-793">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="23392-794">성공적인 배포를 위해 원본 환경을 최소 요구 사항까지 설정하기 위해 필요한 사항에 대한 재구성 검사 목록을 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-794">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="23392-795">필요한 장치 하드웨어 요구 사항을 충족하는 경우 기존 장치에 대한 업그레이드 지침을 Windows 10 Enterprise로 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-795">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="23392-796">기존 배포 움직임을 지원하기 위한 업그레이드 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-796">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="23392-797">FastTrack은 Windows 10으로의 준비된 업그레이드를 위한 지침을 권장하고 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-797">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="23392-798">Windows 정리 이미지 설치 및 Windows Autopilot 배포 시나리오에서도 지침을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-798">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="23392-799">Windows 10 배포의 일부로 Configuration Manager를 사용하여 Microsoft 365 앱을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-799">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="23392-800">조직이 기존 Configuration Manager 환경 또는 Microsoft 365를 사용하여 Windows 10 Enterprise 및 Microsoft 365 앱을 최신으로 유지 하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-800">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="23392-801">
  <strong>다음은 범위를 벗어나는 예제입니다. </strong>  
</span><span class="sxs-lookup"><span data-stu-id="23392-801">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="23392-802">Configuration Manager를 현재 분기로 업그레이드.</span><span class="sxs-lookup"><span data-stu-id="23392-802">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="23392-803">Windows 10 배포용 사용자 지정 이미지 만들기.</span><span class="sxs-lookup"><span data-stu-id="23392-803">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="23392-804">Windows 10 배포용 배포 스크립트 만들기 및 지원</span><span class="sxs-lookup"><span data-stu-id="23392-804">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="23392-805">Windows 10 시스템을 BIOS에서 UEFI(Unified Extensible Firmware Interface)로 변환.</span><span class="sxs-lookup"><span data-stu-id="23392-805">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="23392-806">Windows 10 보안 기능 활성화.</span><span class="sxs-lookup"><span data-stu-id="23392-806">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="23392-807">PXE(Preboot Execution Environment) 부팅을 위해 WDS(Windows Deployment Services) 구성.</span><span class="sxs-lookup"><span data-stu-id="23392-807">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="23392-808">Windows 10 이미지를 캡처하여 배포하는 데 MDT(Microsoft Deployment Toolkit) 사용.</span><span class="sxs-lookup"><span data-stu-id="23392-808">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="23392-809">USMT(User State Migration Tool) 사용.</span><span class="sxs-lookup"><span data-stu-id="23392-809">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="23392-810">Microsoft 파트너에게 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">이러한</a> 서비스에 대한 지원을 요청하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-810">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="23392-811">PC 업그레이드의 경우, 다음 요구 사항을 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-811">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="23392-812">원본 OS: Windows 7 Enterprise 또는 Professional, Windows 8.1 Enterprise 또는 Professional</span><span class="sxs-lookup"><span data-stu-id="23392-812">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="23392-813">장치: 데스크톱, 전자 필기장 또는 태블릿 폼 팩터.</span><span class="sxs-lookup"><span data-stu-id="23392-813">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="23392-814">대상 OS: 창 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="23392-814">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="23392-815">인프라 업그레이드의 경우, 다음 요구 사항을 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-815">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="23392-816">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="23392-816">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="23392-817">Configuration Manager 버전은 Windows 10 대상 버전에서 지원해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-817">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="23392-818">자세한 내용은 <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager에서 Windows 10 지원</a>에서 Configuration Manager 지원 표를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-818">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="23392-819"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="23392-819"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="23392-820">Microsoft Defender Advanced Threat Protection (ATP)는 엔터프라이즈 네트워크가 고급 위협을 방지, 탐지, 조사 및 대응하는 데 도움이 되도록 설계된 플랫폼입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-820">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="23392-821">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-821">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="23392-822">끝점을 보호하는 기술을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-822">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="23392-823">끝점 보호 및 장치 제한 프로필 구성</span><span class="sxs-lookup"><span data-stu-id="23392-823">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="23392-824">OS 버전 및 장치 관리(Intune, Microsoft Endpoint Configuration Manager, GPOS(그룹 정책 개체) 및 타사 구성 포함) 및 Windows Defender AV 서비스 또는 기타 끝점 보안 소프트웨어의 상태를 평가합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-824">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="23392-825">Windows AV 서비스 또는 기타 끝점 보안 소프트웨어의 상태 평가</span><span class="sxs-lookup"><span data-stu-id="23392-825">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="23392-826">네트워크 트래픽을 제한하는 Proxies 및 방화벽 평가</span><span class="sxs-lookup"><span data-stu-id="23392-826">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="23392-827">온보딩 끝점을 사용하여 ATP 에이전트 프로필을 배포하는 방법을 설명하여 Microsoft Defender ATP 서비스를 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="23392-827">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="23392-828">다음에 대한 배포 지침, 구성 지원 및 교육:</span><span class="sxs-lookup"><span data-stu-id="23392-828">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="23392-829">위협 및 취약성 관리.</span><span class="sxs-lookup"><span data-stu-id="23392-829">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-830">공격 표면 감소.</span><span class="sxs-lookup"><span data-stu-id="23392-830">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-831">차세대 보호.</span><span class="sxs-lookup"><span data-stu-id="23392-831">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-832">끝점 감지 및 대응.</span><span class="sxs-lookup"><span data-stu-id="23392-832">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-833">자동화된 조사 및 조치.</span><span class="sxs-lookup"><span data-stu-id="23392-833">Automated investigation and remediation.</span></span>  
  </li>
<li> <span data-ttu-id="23392-834">Microsoft Defender ATP(Windows E5 또는 Microsoft 365 E5 라이선스 필요)</span><span class="sxs-lookup"><span data-stu-id="23392-834">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
<li>  
  <span data-ttu-id="23392-835">보안 점수.</span><span class="sxs-lookup"><span data-stu-id="23392-835">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="23392-836">시뮬레이션 및 자습서 검토(예: 연습 시나리오, 가짜 맬웨어 및 자동화된 조사).</span><span class="sxs-lookup"><span data-stu-id="23392-836">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="23392-837">보고 및 위협 분석 기능 개요</span><span class="sxs-lookup"><span data-stu-id="23392-837">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="23392-838">Office 365 ATP와 Microsoft Defender ATP 통합.</span><span class="sxs-lookup"><span data-stu-id="23392-838">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="23392-839">Microsoft Defender 보안 센터 포털 탐색.</span><span class="sxs-lookup"><span data-stu-id="23392-839">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="23392-840">다음 운영 체제는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-840">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="23392-841">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="23392-841">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-842">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="23392-842">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-843">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="23392-843">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-844">Windows Server 2019 Core Edition</span><span class="sxs-lookup"><span data-stu-id="23392-844">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-845">Windows Server Semi-Annual 채널(SAC) 버전 1803.</span><span class="sxs-lookup"><span data-stu-id="23392-845">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-846">macOS 버전 10.13, 10.14 및 10.15.</span><span class="sxs-lookup"><span data-stu-id="23392-846">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="23392-847">
<strong>참고:</strong> 모든 Windows Server 버전은 최신 버전의 System Center Configuration Manager 2012(버전 1012 R2, 1511 또는 1602) 또는 Microsoft Endpoint Configuration Manager(버전 2002 이상)에서 관리해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-847">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="23392-848"></li>
</ul>

<strong>다음은 범위를 벗어나는 예제입니다. </strong>  
</span><span class="sxs-lookup"><span data-stu-id="23392-848"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="23392-849">고객의 수정 활동에 대한 프로젝트 관리.</span><span class="sxs-lookup"><span data-stu-id="23392-849">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="23392-850">현장 지원.</span><span class="sxs-lookup"><span data-stu-id="23392-850">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="23392-851">지속적인 관리와 위협 대응.</span><span class="sxs-lookup"><span data-stu-id="23392-851">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="23392-852">다음 Microsoft Defender ATP 에이전트에 대한 온보딩 또는 구성:</span><span class="sxs-lookup"><span data-stu-id="23392-852">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="23392-853">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="23392-853">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-854">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="23392-854">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-855">Linux.</span><span class="sxs-lookup"><span data-stu-id="23392-855">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-856">모바일 장치(Android 및 iOS).</span><span class="sxs-lookup"><span data-stu-id="23392-856">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="23392-857">서버 온보더링 및 구성:</span><span class="sxs-lookup"><span data-stu-id="23392-857">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="23392-858">오프라인 통신을 위한 프록시 서버 구성</span><span class="sxs-lookup"><span data-stu-id="23392-858">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-859">다운 수준 Configuration Manager 인스턴스 및 버전에서 Configuration Manager 배포 패키지 구성</span><span class="sxs-lookup"><span data-stu-id="23392-859">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-860">Azure 보안 센터에 서버 온보더링</span><span class="sxs-lookup"><span data-stu-id="23392-860">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-861">Configuration Manager에서 관리되지 않는 서버입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-861">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="23392-862">macOS 온보더링 및 구성:</span><span class="sxs-lookup"><span data-stu-id="23392-862">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="23392-863">수동 Intune 기반 배포.</span><span class="sxs-lookup"><span data-stu-id="23392-863">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-864">JAMF 기반 배포.</span><span class="sxs-lookup"><span data-stu-id="23392-864">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="23392-865">기타 MDM(모바일 장치 관리) 제품 기반 배포.</span><span class="sxs-lookup"><span data-stu-id="23392-865">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-866">수동 배포.</span><span class="sxs-lookup"><span data-stu-id="23392-866">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="23392-867">다음 공격 표면 감소에 대한 기능:</span><span class="sxs-lookup"><span data-stu-id="23392-867">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="23392-868">하드웨어 기반 격리.</span><span class="sxs-lookup"><span data-stu-id="23392-868">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-869">앱 컨트롤.</span><span class="sxs-lookup"><span data-stu-id="23392-869">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-870">악용 방지.</span><span class="sxs-lookup"><span data-stu-id="23392-870">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-871">네트워크 방화벽.</span><span class="sxs-lookup"><span data-stu-id="23392-871">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="23392-872">Microsoft 위협 전문가 등록 또는 구성.</span><span class="sxs-lookup"><span data-stu-id="23392-872">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="23392-873">API 또는 SIEM(보안 정보 및 이벤트 관리) 연결을 검토하는 구성 또는 교육</span><span class="sxs-lookup"><span data-stu-id="23392-873">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="23392-874">MTP(Microsoft 위협 방지) 등록 또는 구성.</span><span class="sxs-lookup"><span data-stu-id="23392-874">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="23392-875">고급 헌팅에 대한 교육 또는 지침.</span><span class="sxs-lookup"><span data-stu-id="23392-875">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="23392-876">Kusto 쿼리의 사용 또는 생성에 대한 교육 또는 지침입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-876">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="23392-877">Microsoft 파트너에게 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">이러한</a> 서비스에 대한 지원을 요청하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-877">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="23392-878">Windows Virtual Desktop</span><span class="sxs-lookup"><span data-stu-id="23392-878">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="23392-879"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="23392-879"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="23392-880"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="23392-880"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="23392-881"><strong>원본 환경 기대치</strong></span><span class="sxs-lookup"><span data-stu-id="23392-881"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="23392-882"><strong>Windows Virtual Desktop</strong></span><span class="sxs-lookup"><span data-stu-id="23392-882"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="23392-883">Windows Virtual Desktop(데스크톱 및 앱 가상화 서비스)에 온보드하기 위한 배포 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-883">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="23392-884">Windows Virtual Desktop은 Windows 10 다중 세션 환경을 활용하며 Microsoft 365에 대한 통합 보안 및 관리를 통해 엔터프라이즈용 Microsoft 365 앱에 최적화되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-884">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="23392-885">다음에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-885">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="23392-886">다음을 사용하여 Windows 10 Enterprise 다중 세션 및 엔터프라이즈용 Microsoft 365 앱을 사용하여 Windows Virtual Desktop 환경을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-886">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="23392-887">Azure 마켓플레이스 이미지.</span><span class="sxs-lookup"><span data-stu-id="23392-887">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="23392-888">공유 이미지.</span><span class="sxs-lookup"><span data-stu-id="23392-888">Shared image.</span></span></li>
<li><span data-ttu-id="23392-889">ODT(Office 배포 Toolkit)</span><span class="sxs-lookup"><span data-stu-id="23392-889">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="23392-890">FSLogix 구성:</span><span class="sxs-lookup"><span data-stu-id="23392-890">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="23392-891">프로필 컨테이너를 사용하여 FSLogix 에이전트 배포</span><span class="sxs-lookup"><span data-stu-id="23392-891">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="23392-892">Office 컨테이너를 통해 FSLogix 에이전트 배포</span><span class="sxs-lookup"><span data-stu-id="23392-892">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="23392-893">콘텐츠 제외를 통해 FSLogix 폴더 구성</span><span class="sxs-lookup"><span data-stu-id="23392-893">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="23392-894">Microsoft Edge 배포.</span><span class="sxs-lookup"><span data-stu-id="23392-894">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="23392-895">Microsoft Teams 배포.</span><span class="sxs-lookup"><span data-stu-id="23392-895">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="23392-896">Windows 가상 데스크톱 클라이언트를 사용하여 연결</span><span class="sxs-lookup"><span data-stu-id="23392-896">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="23392-897">

<strong>다음은 범위를 벗어나는 예제입니다.</strong>
</span><span class="sxs-lookup"><span data-stu-id="23392-897">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="23392-898">고객의 Windows Virtual Desktop 배포 프로젝트 관리</span><span class="sxs-lookup"><span data-stu-id="23392-898">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="23392-899">타사 앱 가상화 및 배포</span><span class="sxs-lookup"><span data-stu-id="23392-899">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="23392-900">사용자 지정 이미지.</span><span class="sxs-lookup"><span data-stu-id="23392-900">Custom images.</span></span></li>
<li><span data-ttu-id="23392-901">VMware 및 Citrix와 관련된 마이그레이션 및 시나리오</span><span class="sxs-lookup"><span data-stu-id="23392-901">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="23392-902">Linux 시나리오.</span><span class="sxs-lookup"><span data-stu-id="23392-902">Linux scenarios.</span></span></li>
<li><span data-ttu-id="23392-903">사용자 프로필 변환 또는 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="23392-903">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="23392-904">Microsoft 파트너에게 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">이러한</a> 서비스에 대한 지원을 요청하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-904">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="23392-905">다음이 이미 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-905">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="23392-906"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop 라이선스 요구 사항.</a></span><span class="sxs-lookup"><span data-stu-id="23392-906"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="23392-907">Azure 네트워킹:</span><span class="sxs-lookup"><span data-stu-id="23392-907">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="23392-908">VNET(가상 네트워크) 만들기 및 서브넷팅</span><span class="sxs-lookup"><span data-stu-id="23392-908">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="23392-909">방화벽 및 네트워크 보안 그룹</span><span class="sxs-lookup"><span data-stu-id="23392-909">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="23392-910">VPN 및 ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="23392-910">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="23392-911">On-premises에서 Azure로 라우팅</span><span class="sxs-lookup"><span data-stu-id="23392-911">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="23392-912">Windows Virtual Desktop에 대한 연결을 허용하는 방화벽 규칙입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-912">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="23392-913">자세한 내용은 지원되는 원격 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">데스크톱 클라이언트를 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="23392-913">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="23392-914">Azure AD 일반 설정:</span><span class="sxs-lookup"><span data-stu-id="23392-914">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="23392-915">ID <i>전략(다음 세</i> 가지 옵션 중 하나만 사용할 수 있습니다.
</span><span class="sxs-lookup"><span data-stu-id="23392-915">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="23392-916">Azure에서 Azure AD Connect가 있는 Active Directory.</span><span class="sxs-lookup"><span data-stu-id="23392-916">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="23392-917">VPN 또는 ExpressRoute를 통해 Azure AD Connect가 있는 Active Directory에 대해 Azure AD Connect를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-917">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="23392-918">AD DS(Active Directory 도메인 서비스)</span><span class="sxs-lookup"><span data-stu-id="23392-918">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="23392-919">App Assure</span><span class="sxs-lookup"><span data-stu-id="23392-919">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="23392-920"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="23392-920"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="23392-921"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="23392-921"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="23392-922"><strong>원본 환경 기대치</strong></span><span class="sxs-lookup"><span data-stu-id="23392-922"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="23392-923"><strong>앱 보증</strong></span><span class="sxs-lookup"><span data-stu-id="23392-923"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="23392-924">App Assure는 Windows 10 및 Microsoft 365 앱 호환성 문제를 해결하도록 설계된 서비스입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-924">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="23392-925">App Assure 서비스를 요청하는 경우 적격 구독을 사용할 경우 추가 비용으로 유효한 앱 문제를 해결하기 위해 함께 작업합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-925">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="23392-926">또한 Windows Virtual Desktop 및 Microsoft Edge를 배포할 때 호환성 문제가 있는 고객에게 지침을 제공하고 호환성 문제를 해결하기 위한 모든 합리적 노력을 다합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-926">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="23392-927">다음 Microsoft 제품에 배포된 앱에 대한 수정 지원을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-927">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="23392-928"><strong>Windows 10(ARM64 </strong> 장치 포함)</span><span class="sxs-lookup"><span data-stu-id="23392-928"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="23392-929"><strong>Microsoft 365 앱</strong>  </span><span class="sxs-lookup"><span data-stu-id="23392-929"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="23392-930"><strong>Microsoft Edge -</strong> 배포 지침은 Microsoft Edge 채널 <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">개요를 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="23392-930"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="23392-931"><strong>Windows 가상 데스크톱</strong> - 자세한 내용은 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">Windows Virtual Desktop이란?</a> 및 Windows 10 Enterprise 다중 세션 <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">FAQ를 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="23392-931"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="23392-932">

<strong>다음은 범위를 벗어나는 예제입니다. </strong>  
</span><span class="sxs-lookup"><span data-stu-id="23392-932">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="23392-933">Windows 10 및 Microsoft 365 앱에서 작동하거나 작동하지 않는 기능을 확인하기 위한 앱 인벤토리 및 테스트.</span><span class="sxs-lookup"><span data-stu-id="23392-933">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="23392-934">이 프로세스에 관한 자세한 지침을 보려면 <a href="https://go.microsoft.com/fwlink/?linkid=2080140">데스크톱 배포 센터</a>를 방문하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-934">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="23392-935">더 심화된 업그레이드 준비 평가에 관심이 있으신 경우 <a href="https://go.microsoft.com/fwlink/?linkid=2053818">최신 데스크톱 평가에 관한 고객 요청</a> 양식을 작성하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-935">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="23392-936">타사 ISV 앱에서 Windows 10 호환성 및 지원 정책 연구</span><span class="sxs-lookup"><span data-stu-id="23392-936">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="23392-937">자세한 내용은 <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">데스크톱 분석</a>을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-937">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="23392-938">앱 패키지 전용 서비스.</span><span class="sxs-lookup"><span data-stu-id="23392-938">App packaging-only services.</span></span> <span data-ttu-id="23392-939">그렇지만 App Assure 팀은 고객 환경에 배포될 수 있도록 하기 위해 WIndows 10에 대해 수정한 앱을 패키지로 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="23392-939">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="23392-940">

<strong>고객 책임에는 다음이 포함됩니다.</strong>  
</span><span class="sxs-lookup"><span data-stu-id="23392-940">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="23392-941">앱 목록 만들기.</span><span class="sxs-lookup"><span data-stu-id="23392-941">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="23392-942">Windows 10 및 Microsoft 365 앱에서 앱의 유효성 검증.</span><span class="sxs-lookup"><span data-stu-id="23392-942">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="23392-943">
<strong>참고:</strong>  Microsoft는 소스 코드를 변경할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-943">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="23392-944">그러나 사용자 앱의 소스 코드를 사용할 수 있는 경우 App Assure 팀이 앱 개발자에게 지침을 제공할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-944">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="23392-945">Microsoft 파트너에게 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">이러한</a> 서비스에 대한 지원을 요청하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-945">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="23392-946"><strong>Windows 10 및 Microsoft 365 앱</strong>
</span><span class="sxs-lookup"><span data-stu-id="23392-946"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="23392-947">Windows 7, Windows 8.1, Office 2010 및 Office 2013에서 작동하는 앱은 Windows 10 및 Microsoft 365 앱에서도 작동합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-947">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="23392-948">
<strong>Windows 10 on ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="23392-948">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="23392-949">Windows 7, Office 2010 이상 버전에서 작동한 앱은 ARM64 장치의 Windows 10 및 Microsoft 365 앱에서도 작동합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-949">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="23392-950">
  <strong>참고:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="23392-950">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="23392-951">x64(64비트) 에뮬ation은 <a href="https://insider.windows.com/">Windows Insider Program에</a>참여하는 고객을 위해 미리 보기에서 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-951">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="23392-952">Windows 10 버전 2004 이상에서 Windows가 아닌 고객의 경우 ARM64 Photoshop은 OpenCL 및 OpenGL 호환성 팩을 사용하여 <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">지원됩니다.</a></span><span class="sxs-lookup"><span data-stu-id="23392-952">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="23392-953">Windows Insider Program의 고객은 추가 앱에 사용할 OpenCL 및 OpenGL 호환성 팩의 Insider 버전을 다운로드할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-953">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="23392-954">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="23392-954">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="23392-955">웹앱 또는 사이트가 Internet Explorer 11, 지원되는 Google Chrome 버전 또는 모든 버전의 Microsoft Edge에서 작동하면 Microsoft Edge에서도 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-955">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-956">웹이 지속적으로 진화하고 있는 경우 Microsoft Edge에 대해 게시된 알려진 사이트 호환성에 영향을 미치는 변경 사항 목록을 <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">검토해야 합니다.</a></span><span class="sxs-lookup"><span data-stu-id="23392-956">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="23392-957">
  <strong>Windows 가상 데스크톱 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="23392-957">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="23392-958">Windows Server RDSH (원격 데스크톱 세션 호스트)에서 실행되는 가상화된 앱도 Windows Virtual Desktop의 일부로 Windows 10 Enterprise 멀티 세션에서 실행됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-958">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-959">Windows 7 또는 Windows 10 VDI(가상 데스크톱 인프라) 환경에서 실행되는 앱은 Windows Virtual Desktop의 일부로 Windows 7 Enterprise 및 Windows 10 Enterprise에서도 실행됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-959">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-960">Windows 7 또는 Windows 10 클라이언트 장치에서 실행되는 앱도 Windows Virtual Desktop의 일부로 Windows 7 Enterprise 및 Windows 10 Enterprise에서 실행됩니다.</span><span class="sxs-lookup"><span data-stu-id="23392-960">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="23392-961">
  <strong>참고:</strong> Windows 10 Enterprise 다중 세션 호환성 제외 및 제한은 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-961">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="23392-962">제한된 하드웨어 리디렉션.</span><span class="sxs-lookup"><span data-stu-id="23392-962">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-963">A/V-집약적인 앱은 줄어든 용량으로 실행될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-963">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="23392-964">16비트 앱은 64비트 Windows Virtual Desktop에서 지원되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-964">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="23392-965">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="23392-965">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="23392-966"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="23392-966"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="23392-967"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="23392-967"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="23392-968"><strong>원본 환경 기대치</strong></span><span class="sxs-lookup"><span data-stu-id="23392-968"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="23392-969"><strong>Microsoft Edge(Windows</strong> 10 Enterprise 고객용)</span><span class="sxs-lookup"><span data-stu-id="23392-969"><strong>Microsoft Edge</strong> (for Windows 10 Enterprise customers)</span></span></td>
<td><ul>
<li>  <span data-ttu-id="23392-970">Microsoft는 Microsoft Endpoint Manager(Microsoft Endpoint Configuration Manager 또는 Intune)를 사용하여 Windows 10 Enterprise에 Microsoft Edge 배포에 대한 원격 배포 지침 및 호환성 지원을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-970">We provide remote deployment guidance and compatibility assistance for: Deploying Microsoft Edge on Windows 10 Enterprise with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="23392-971">Microsoft Edge 구성(그룹 정책 또는 Intune 앱 구성 및 앱 정책 사용)</span><span class="sxs-lookup"><span data-stu-id="23392-971">Microsoft Edge configuration (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="23392-972">사이트 목록에서 사용이 필요할 수 있는 사이트 목록을 Internet Explorer 있습니다.</span><span class="sxs-lookup"><span data-stu-id="23392-972">Inventory the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="23392-973">기존 엔터프라이즈 Internet Explorer 모드 사용</span><span class="sxs-lookup"><span data-stu-id="23392-973">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span>  
  <span data-ttu-id="23392-974">또한 웹 앱 또는 사이트가 Internet Explorer 또는 Google Chrome과 호환되는 경우 추가 비용 없음으로 문제를 해결하기 위한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="23392-974">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="23392-975">자세한 <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">내용은 App Assure를</a> 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="23392-975">See <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">App Assure</a> for more details.</span></span>  </li>
</ul><span data-ttu-id="23392-976">

<strong>다음은 범위를 벗어나는 예제입니다. </strong>  
</span><span class="sxs-lookup"><span data-stu-id="23392-976">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="23392-977">고객의 Microsoft Edge 배포에 대한 프로젝트 관리입니다.</span><span class="sxs-lookup"><span data-stu-id="23392-977">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="23392-978">현장 지원.</span><span class="sxs-lookup"><span data-stu-id="23392-978">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
