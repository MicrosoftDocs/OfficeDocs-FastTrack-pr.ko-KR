---
title: 제품 및 기능
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Normal
ms.collection: FastTrack
description: 이 항목에서는 FastTrack이 지원되는 작업 시나리오와 시작하기 전에 필요한 원본 환경 기대치에 대해 자세히 설명합니다. 현재 설정에 따라, 성공적인 온보딩에 필요한 최소 한도로 원본 환경을 가져오는 재구성 계획을 만드세요.
ms.openlocfilehash: d25c1df8e628f14487952cacc86ccf8fb9dad8c1
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817703"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="b54c0-104">제품 및 기능</span><span class="sxs-lookup"><span data-stu-id="b54c0-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="b54c0-105">FastTrack에서 지원되는 서비스 및 시나리오</span><span class="sxs-lookup"><span data-stu-id="b54c0-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="b54c0-106">이 항목에서는 FastTrack이 지원되는 작업 시나리오와 시작하기 전에 필요한 원본 환경 기대치에 대해 자세히 설명합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="b54c0-107">현재 설정에 따라, 성공적인 온보딩에 필요한 최소 한도로 원본 환경을 가져오는 재구성 계획을 만드세요.</span><span class="sxs-lookup"><span data-stu-id="b54c0-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="b54c0-108">FastTrack은 핵심 기능(모든 Microsoft Online Services에 공통된)을 사용한 다음 적격한 각 온보딩 서비스를 사용하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="b54c0-109">일반</span><span class="sxs-lookup"><span data-stu-id="b54c0-109">General</span></span>](#general)
  - [<span data-ttu-id="b54c0-110">Office 365</span><span class="sxs-lookup"><span data-stu-id="b54c0-110">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="b54c0-111">Enterprise Mobility & 보안</span><span class="sxs-lookup"><span data-stu-id="b54c0-111">Enterprise Mobility & Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="b54c0-112">Windows 10</span><span class="sxs-lookup"><span data-stu-id="b54c0-112">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="b54c0-113">App Assure</span><span class="sxs-lookup"><span data-stu-id="b54c0-113">App Assure</span></span>](Win-10-app-assure.md)
  - [<span data-ttu-id="b54c0-114">새로운 Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="b54c0-114">The new Microsoft Edge</span></span>](Win-10-microsoft-edge.md)

> [!NOTE]
> <span data-ttu-id="b54c0-115">Office 365 미국 정부에 대한 원본 환경 기대치에 대한 정보는 [Office 365 미국 정부에 대한 소스 환경 기대치를 참조하세요.](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)</span><span class="sxs-lookup"><span data-stu-id="b54c0-115">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span>
 
## <a name="general"></a><span data-ttu-id="b54c0-116">일반</span><span class="sxs-lookup"><span data-stu-id="b54c0-116">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="b54c0-117"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-117"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="b54c0-118"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-118"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="b54c0-119"><strong>원본 환경 기대</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-119"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b54c0-120"><strong>핵심 온보딩</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-120"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-121">Microsoft는 서비스 프로비전, 테넌트 및 ID 통합이 포함되는 핵심 온보딩에 대한 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-121">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="b54c0-122">또한 보안, 네트워크 연결 및 규정 준수에 대한 토론을 포함하여 Exchange Online, SharePoint Online 및 Microsoft Teams와 같은 온보딩 서비스에 기초 사안을 제공하기 위한 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">단계도 포함됩니다.</a></span><span class="sxs-lookup"><span data-stu-id="b54c0-122">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="b54c0-123">하나 이상의 적합한 서비스에 대한 온보딩은 핵심 온보딩이 완료되면 시작됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-123">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="b54c0-124"></li>
</ul>  

<strong> ID 통합 </strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-124"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="b54c0-125">다음에 대한 원격 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-125">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="b54c0-126">Azure AD Connect 설치 및 구성(단일 또는 다중 포리스트) 및 라이선스(그룹 기반 라이선싱 포함)를 포함하여 Azure Directory(Azure AD)에 동기화를 위한 온-프레미스 Active Directory ID 준비.</span><span class="sxs-lookup"><span data-stu-id="b54c0-126">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="b54c0-127">그룹 기반 라이선싱 사용을 포함하여 대량 가져오기 및 라이선스를 포함한 클라우드 ID 만들기</span><span class="sxs-lookup"><span data-stu-id="b54c0-127">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="b54c0-128">클라우드 이동 과정에 올바른 인증 방법, 암호 해시 동기화, 통과 인증 또는 AD FS(Active Directory Federation Services)를 원하는지 확인하고 사용하도록 설정.</span><span class="sxs-lookup"><span data-stu-id="b54c0-128">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="b54c0-129">단일 Active Directory 포리스트 및 ID가 Azure AD Connect 도구와 동기화된 고객에 대해 AD FS를 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="b54c0-129">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="b54c0-130">이 작업을 Windows Server 2012 R2 Active Directory Federation Services 2.0 이상이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-130">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="b54c0-131">암호 해시 동기화 또는 통과 인증을 사용하여 AD FS에서 Azure AD로 인증을 마이그레이션하는 경우</span><span class="sxs-lookup"><span data-stu-id="b54c0-131">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="b54c0-132">SSO(Single Sign-On)에 대해 AD FS에서 Azure ADFS로 의지와 미리 통합된 앱(예: Azure AD 갤러리 소프트웨어-A-Service(SaaS) 앱)을 AD FS에서 Azure AD로 마이그레이션</span><span class="sxs-lookup"><span data-stu-id="b54c0-132">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="b54c0-133">Azure AD 갤러리에서 SSO와 SaaS 앱 통합 사용</span><span class="sxs-lookup"><span data-stu-id="b54c0-133">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="b54c0-134">앱 통합 자습서 목록에 나열된 사전 통합된 SaaS 앱에 대해 자동 사용자 프로비저닝을 활성화합니다(Azure AD 갤러리 SaaS 앱 및 아웃바운드 프로비저닝으로만 제한됨). <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a></span><span class="sxs-lookup"><span data-stu-id="b54c0-134">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="b54c0-135"><strong>네트워크 사용 </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="b54c0-135"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="b54c0-136">FastTrack 혜택의 일부로 클라우드 서비스에 연결하여 Microsoft 365의 최고 수준의 성능을 보장하시기 바라는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-136">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="b54c0-137"><strong>Active Directory 포리스트</strong> 이러한 기능의 포리스트 수준은 다음 포리스트 구성을 사용하여 Windows Server 2003 이상으로 설정되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-137"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-138">단일 Active Directory 포리스트.</span><span class="sxs-lookup"><span data-stu-id="b54c0-138">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-139">단일 Active Directory 계정 포리스트 및 리소스 포리스트(Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype) 토폴로지</span><span class="sxs-lookup"><span data-stu-id="b54c0-139">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-140">여러 개의 Active Directory 계정 포리스트 및 리소스 포리스트(Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype) 토폴로지</span><span class="sxs-lookup"><span data-stu-id="b54c0-140">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-141">포리스트 중 하나가 Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype가 있는 중앙 집중식 Active Directory 계정 포리스트인 여러 Active Directory 계정 포리스트</span><span class="sxs-lookup"><span data-stu-id="b54c0-141">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-142">각각이 자체 Exchange 조직을 갖는 다중 Active Directory 계정 포리스트</span><span class="sxs-lookup"><span data-stu-id="b54c0-142">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-143">테넌트를 구성하고 필요한 경우 Azure Active Directory와 통합하는 데 필요한 작업입니다.   </span><span class="sxs-lookup"><span data-stu-id="b54c0-143">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.   </span></span></li>
</ul><span data-ttu-id="b54c0-144">
  <strong>중요:</strong>  </span><span class="sxs-lookup"><span data-stu-id="b54c0-144">
  <strong>Important:</strong>  </span></span><ul>
<li>  <span data-ttu-id="b54c0-145">다중 포리스트 Active Directory 시나리오의 경우 Lync 2010, Lync 2013 또는 비즈니스용 Skype를 배포할 때 Exchange와 동일한 Active Directory를 배포해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-145">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-146">여러 Exchange 조직이 Exchange 다중 하이브리드 구성의 여러 Exchange 조직으로 포리스트를 구현하는 경우 원본 포리스트 간의 공유된 UPN(사용자 계정 이름) 네임스페이스는 지원되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-146">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="b54c0-147">Exchange 조직 간의 기본 SMTP 네임스페이스도 구분해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-147">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="b54c0-148">자세한 내용은 <a href="https://go.microsoft.com/fwlink/?linkid=845444">Active Directory 포리스트가 여러 개인 하이브리드 배포를 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="b54c0-148">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-149">모든 다중 포리스트 구성에서 AD FS(Active Directory Federation Services) 배포는 다범위를 벗어나는 것입니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-149">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="b54c0-150">이에 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">대한 지원을</a> 받기만 하면 Microsoft 파트너에 문의하세요.</span><span class="sxs-lookup"><span data-stu-id="b54c0-150">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b54c0-151"><strong>Microsoft 365 앱</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-151"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-152">다음에 대한 원격 배포 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-152">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-153">배포 문제 해결</span><span class="sxs-lookup"><span data-stu-id="b54c0-153">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-154">Microsoft 365 관리 센터 및 Windows PowerShell을 사용하여 최종 사용자 및 디바이스 기반 라이선스 할당</span><span class="sxs-lookup"><span data-stu-id="b54c0-154">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-155">간편 실행을 사용하여 Office 365 포털에서 Microsoft 365 앱 설치</span><span class="sxs-lookup"><span data-stu-id="b54c0-155">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-156">iOS 또는 Android 장치에 Office Mobile 앱(에: Outlook Mobile, Word Mobile, Excel Mobile 및 PowerPoint Mobile) 설치</span><span class="sxs-lookup"><span data-stu-id="b54c0-156">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-157">Office 365 배포 도구를 사용하여 업데이트 설정 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-157">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-158">로컬 또는 클라우드 설치의 선택 및 설치</span><span class="sxs-lookup"><span data-stu-id="b54c0-158">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-159">배포 패티지를 구성하기 위해 Office 사용자 지정 도구 또는 네이티브 XML을 사용하여 Office 배포 도구 구성 XML 작성</span><span class="sxs-lookup"><span data-stu-id="b54c0-159">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-160">Microsoft Endpoint Configuration Manager를 사용하여 배포(Endpoint Configuration Manager 패키지 생성에 대한 지원 포함)</span><span class="sxs-lookup"><span data-stu-id="b54c0-160">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="b54c0-161">또한 이전 버전의 Office와 함께 작동한 매크로나 추가 기능을 사용하고 호환성 문제가 발생하는 경우 App Assure 프로그램을 통해 추가 비용 없이 호환성 문제를 해결하는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-161">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="b54c0-162">자세한 내용은 <a href="#windows-10">Windows 10의</a> <strong>App Assure</strong> 부분을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="b54c0-162">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="b54c0-163">온라인 클라이언트 소프트웨어는 Microsoft 365 및 Office의 시스템 요구 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">사항에 정의된 적어도 수준으로 있어야 합니다.</a></span><span class="sxs-lookup"><span data-stu-id="b54c0-163">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b54c0-164"><strong>네트워크 상태</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-164"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-165">Microsoft는 조직의 사이트가 네트워크 연결의 Microsoft에서 정도를 어떻게 정도 조정하고 운영하는지를 보여주는 환경의 주요 네트워크 연결 데이터를 얻고 고석할 때 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">원격 지침을 제공합니다.</a></span><span class="sxs-lookup"><span data-stu-id="b54c0-165">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="b54c0-166">이렇게 하면 마이그레이션 결과, 사용자 환경, 서비스 성능 및 안정성에 직접적으로 영향을 미치는 네트워크 점수가 강조 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-166">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="b54c0-167">또한 네트워크 점수를 개선하는 데 도움이 되는 이 데이터가 강조하는 수정 단계를 안내합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-167">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="b54c0-168">Microsoft 365 관리 센터 액세스</span><span class="sxs-lookup"><span data-stu-id="b54c0-168">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-169">Microsoft 365 앱의 업데이트 버전이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-169">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-170"><a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 관리 센터(미리 보기)에서 네트워크 성능 권장 사항에 따나는 위치 서비스입니다.</a></span><span class="sxs-lookup"><span data-stu-id="b54c0-170">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="b54c0-171">Office 365</span><span class="sxs-lookup"><span data-stu-id="b54c0-171">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="b54c0-172"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-172"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="b54c0-173"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-173"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="b54c0-174"><strong>원본 환경 기대</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-174"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b54c0-175"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-175"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-176">Exchange Online의 경우 조직에서 전자 메일 사용 준비를 완료하도록 안내합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-176">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="b54c0-177">정확한 단계는 원본 환경 및 전자 메일 마이그레이션 계획에 따라 다릅니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-177">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="b54c0-178">다음에 대한 원격 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-178">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-179">Office 365에서 유효성이 검사된 모든 메일 사용이 가능한 도메인에 대해 EOP(Exchange Online Protection) 기능을 설정합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-179">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-180">Office 365를 가리키도록 메일 교환(MX) 레코드를 설정합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-180">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-181">구독 서비스의 일부인 경우 Office 365 ATP 기능을 설정합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-181">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="b54c0-182">자세한 내용은 이 표의 <strong>Office 365 Advanced Threat Protection</strong> 부분을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="b54c0-182">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-p113">구독 서비스의 일부로 Office 365에서 확인된 모든 메일 사용 가능 도메인에 대한 데이터 손실 방지(DLP) 기능 설정. MX 레코드가 Office 365를 가리키면 완료됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-p113">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="b54c0-p114">구독 서비스의 일부로 Office 365에서 확인된 모든 메일 사용 가능 도메인에 대해 Office 365 메시지 암호화(OME)를 설정합니다. MX 레코드가 Office 365를 가리키면 완료됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-p114">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="b54c0-187">
  <strong>참고:</strong> MRS(사서함 복제 서비스)는 온-프레미스 사서함의 IRM(정보 권한 관리) 전자 메일을 해당 Exchange Online 사서함으로 마이그레이션하려고 시도합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-187">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="b54c0-188">마이그레이션 후 보호된 콘텐츠를 읽는 기능은 클라이언트가 AD RMS(Active Directory Rights Managed Services) 서식 파일을 Azure RMS(Azure Rights Management Service)에 매핑하고 복사하는 방법에 따라 다릅니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-188">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="b54c0-189">방화벽 포트 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-189">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-190">필요한 자동 검색, SPF(보낸 사람 정책 프레임워크), DKIM(Domain-Based Message Authentication, Reporting and Conformance) 및 MX 레코드(필요에 따라)를 비롯한 DNS 설정</span><span class="sxs-lookup"><span data-stu-id="b54c0-190">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="b54c0-191">원본 메시징 환경과 Exchange Online 간 전자 메일 흐름 설정(필요한 경우)</span><span class="sxs-lookup"><span data-stu-id="b54c0-191">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="b54c0-192">원본 메시징 환경에서 Office 365로 메일 마이그레이션 수행</span><span class="sxs-lookup"><span data-stu-id="b54c0-192">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-193">사서함 클라이언트(Windows용 Outlook, 웹용 Outlook, iOS 및 Android용 Outlook) 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-193">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="b54c0-194">
  <strong>데이터 마이그레이션</strong>  </span><span class="sxs-lookup"><span data-stu-id="b54c0-194">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="b54c0-195">Office 365로의 데이터 마이그레이션에 대한 FastTrack 혜택을 사용하는 방법에 대한 자세한 내용은 데이터 <a href="https://review.docs.microsoft.com/fasttrack/data-migration">마이그레이션을 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="b54c0-195">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="b54c0-196">원본 환경은 다음 최소 수준 중 하나로 포함해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-196">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-197">Exchange Server 2003 이후 버전을 사용하는 단일 또는 다중 Exchange 조직</span><span class="sxs-lookup"><span data-stu-id="b54c0-197">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-198">단일 IMAP(Internet Message Access Protocol) 지원 전자 메일 환경</span><span class="sxs-lookup"><span data-stu-id="b54c0-198">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-199">단일 G 제품군 환경(Gmail, 연락처 및 캘린더만)</span><span class="sxs-lookup"><span data-stu-id="b54c0-199">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="b54c0-200">다중 위치 기능에 대한 자세한 내용은 <a href="https://go.microsoft.com/fwlink/?linkid=872776">Exchange Online의 다중 위치 기능을 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="b54c0-200">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="b54c0-201">Project for Office 365, Windows용 Outlook, iOS 및 Android용 Outlook, 비즈니스용 OneDrive 동기화 클라이언트, Power BI Desktop, 비즈니스용 Skype 등의 온라인 클라이언트 소프트웨어는 Microsoft 365 Office의 시스템 요구 사항에 정의된 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">것처럼 최소 수준에 있어야 합니다.</a></span><span class="sxs-lookup"><span data-stu-id="b54c0-201">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="b54c0-202"><strong>Microsoft 정보 거버넌스</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-202"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-203">다음에 대한 원격 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-203">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-204">정보 거버넌스.</span><span class="sxs-lookup"><span data-stu-id="b54c0-204">Information governance.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-205">보존 레이블 및 정책.</span><span class="sxs-lookup"><span data-stu-id="b54c0-205">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-206">레코드 관리.</span><span class="sxs-lookup"><span data-stu-id="b54c0-206">Records management.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-207">삭제 정책.</span><span class="sxs-lookup"><span data-stu-id="b54c0-207">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-208">커뮤니케이션 규정 준수.</span><span class="sxs-lookup"><span data-stu-id="b54c0-208">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-209">내부자 위험 관리.</span><span class="sxs-lookup"><span data-stu-id="b54c0-209">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-210">Advanced eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="b54c0-210">Advanced eDiscovery.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="b54c0-211">일반적으로 핵심 <strong>온보딩 부분과</strong> <a href="#general">관련하여 최소</a>시스템 요구 사항은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-211">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b54c0-212"><strong>Microsoft Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-212"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-213">다음에 대한 원격 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-213">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-214">데이터 분류.</span><span class="sxs-lookup"><span data-stu-id="b54c0-214">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-215">중요한 정보 유형</span><span class="sxs-lookup"><span data-stu-id="b54c0-215">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-216">민감도 레이블 만들기.</span><span class="sxs-lookup"><span data-stu-id="b54c0-216">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-217">민감도 레이블 적용.</span><span class="sxs-lookup"><span data-stu-id="b54c0-217">Applying Sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-218">통합 레이블 구성.</span><span class="sxs-lookup"><span data-stu-id="b54c0-218">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-219">훈훈 가능한 분류자</span><span class="sxs-lookup"><span data-stu-id="b54c0-219">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-220">콘텐츠 탐색기와 활동 탐색기를 사용한 사용자 데이터 확인.</span><span class="sxs-lookup"><span data-stu-id="b54c0-220">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-221">정책을 사용하여 레이블을 게시합니다(수동 및 자동).</span><span class="sxs-lookup"><span data-stu-id="b54c0-221">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="b54c0-222">Microsoft Teams 채팅 및 채널용 DLP(데이터 손실 방지) 정책 만들기</span><span class="sxs-lookup"><span data-stu-id="b54c0-222">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="b54c0-223">일반적으로 핵심 <strong>온보딩 부분과</strong> <a href="#general">관련하여 최소</a>시스템 요구 사항은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-223">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b54c0-224"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-224"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-225">다음에 대한 원격 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-225">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-226">Teams를 지원하기 위해 Exchange Online, SharePoint Online, Office 365 그룹 및 Azure AD에서 최소 요구 사항 확인</span><span class="sxs-lookup"><span data-stu-id="b54c0-226">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-227">방화벽 포트 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-227">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-228">DNS 설정.</span><span class="sxs-lookup"><span data-stu-id="b54c0-228">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-229">Office 365 테넌트에서 팀 확인이 가능합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-229">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-230">사용자 라이선스 사용 또는 사용 안 함.</span><span class="sxs-lookup"><span data-stu-id="b54c0-230">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-231">Teams에 대한 네트워크 평가:</span><span class="sxs-lookup"><span data-stu-id="b54c0-231">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-232">포트 및 끝점 검사</span><span class="sxs-lookup"><span data-stu-id="b54c0-232">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-233">연결 품질 검사</span><span class="sxs-lookup"><span data-stu-id="b54c0-233">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-234">대역폭 예상</span><span class="sxs-lookup"><span data-stu-id="b54c0-234">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="b54c0-235">Teams 앱 정책 구성(Teams 웹 앱, Teams 데스크톱 앱, iOS 및 Android용 Teams 앱)</span><span class="sxs-lookup"><span data-stu-id="b54c0-235">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="b54c0-236">해당하는 경우 다음에 대한 지침도 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-236">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-237">Microsoft Teams 룸 장치:</span><span class="sxs-lookup"><span data-stu-id="b54c0-237">Microsoft Teams Room Devices:</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="b54c0-238">Teams 장치 카탈로그에 나열된 지원되는 전화 및 회의실 장치에 필요한 온라인 <a href="https://go.microsoft.com/fwlink/?linkid=2066478">계정 생성.</a></span><span class="sxs-lookup"><span data-stu-id="b54c0-238">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="b54c0-239">오디오 회의 사용:</span><span class="sxs-lookup"><span data-stu-id="b54c0-239">Enabling Audio Conferencing:</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="b54c0-240">회의 브리지 기본 설정에 대한 조직 설정</span><span class="sxs-lookup"><span data-stu-id="b54c0-240">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-241">회의 브리지를 라이선스가 있는 사용자에게 할당</span><span class="sxs-lookup"><span data-stu-id="b54c0-241">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="b54c0-242">전화 시스템:</span><span class="sxs-lookup"><span data-stu-id="b54c0-242">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-243">클라우드 음성 기본 설정에 대한 조직 설정</span><span class="sxs-lookup"><span data-stu-id="b54c0-243">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-244">통화 플랜 지침(사용 가능한<a href="https://go.microsoft.com/fwlink/?linkid=2066478">시장):</a></span><span class="sxs-lookup"><span data-stu-id="b54c0-244">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-245">라이선스가 있는 사용자에게 번호 할당</span><span class="sxs-lookup"><span data-stu-id="b54c0-245">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-246">UI(사용자 인터페이스)를 통해 최대 999개의 지역 번호 이식 지침</span><span class="sxs-lookup"><span data-stu-id="b54c0-246">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-247">999개가 넘는 번호를 지원하는 지역 번호 이식 SR(서비스 요청)</span><span class="sxs-lookup"><span data-stu-id="b54c0-247">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="b54c0-248">직접 라우팅 지침:</span><span class="sxs-lookup"><span data-stu-id="b54c0-248">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-249">파트너 호스팅 시나리오 또는 단일 사이트에 대한 고객 배포 시나리오의 직접 라우팅 디자인을 위한 조직 설정 지침</span><span class="sxs-lookup"><span data-stu-id="b54c0-249">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for a single site.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="b54c0-250">권한 부여 팀 라이브 이벤트</span><span class="sxs-lookup"><span data-stu-id="b54c0-250">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-251">조직 설정 및 Microsoft Stream에 통합</span><span class="sxs-lookup"><span data-stu-id="b54c0-251">Organization setup and integration into Microsoft Stream.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="b54c0-252">ID가 Office 365용 Azure AD에서 사용하도록 설정된 경우</span><span class="sxs-lookup"><span data-stu-id="b54c0-252">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-253">SharePoint Online에 대해 사용하는 사용자.</span><span class="sxs-lookup"><span data-stu-id="b54c0-253">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-254">Exchange 사서함이 존재합니다(Exchange 하이브리드 구성에 있는 온라인 및 온-프레미스).</span><span class="sxs-lookup"><span data-stu-id="b54c0-254">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="b54c0-255">Office 365 그룹에서 사용되도록 설정됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-255">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="b54c0-256">
  <strong>참고:</strong>   사용자가 할당되고 SharePoint Online 라이선스로 사용하도록 설정되지 않은 경우 Office 365의 비즈니스용 OneDrive 저장소가 제공되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-256">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="b54c0-257">채널에서 계속 파일을 공유할 수 있지만, 사용자는 Office 365에 비즈니스용 OneDrive 저장소가 없이 채팅에서 파일을 공유할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-257">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="b54c0-258">Teams는 SharePoint 온-프레미스를 지원하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-258">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="b54c0-259">
  <strong>참고:</strong>   Exchange Online에 있는 사서함이 있는 모든 사용자 이상적 상태입니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-259">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="b54c0-260">온-프레미스에 속한 사서함이 있는 사용자는 ID를 Azure AD Connect를 통해 Office 365 디렉터리로 동기화해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-260">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="b54c0-261">이러한 Exchange 하이브리드 고객의 경우 사용자 사서함이 온-프레미스인 경우 사용자는 커넥터를 추가하거나 구성할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-261">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="b54c0-262">Microsoft Teams Windows 및 Mac 데스크톱 클라이언트용 설치 관리자는 다음에서 다운로드할 수  <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> 있습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-262">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b54c0-263"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-263"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-264">다음에 대한 원격 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-264">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-265">안전한 링크, 안전한 첨부 파일 및 피싱 방지 사용.</span><span class="sxs-lookup"><span data-stu-id="b54c0-265">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-266">자동화, 조사 및 대응 구성.</span><span class="sxs-lookup"><span data-stu-id="b54c0-266">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-267">공격 시뮬레이터 사용.</span><span class="sxs-lookup"><span data-stu-id="b54c0-267">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-268">보고 및 위협 분석.</span><span class="sxs-lookup"><span data-stu-id="b54c0-268">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="b54c0-269">일반적으로 핵심 <strong>온보딩 부분과</strong> <a href="#general">관련하여 최소</a>시스템 요구 사항은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-269">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b54c0-270"><strong>iOS 및 Android용 Outlook</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-270"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-271">다음에 대한 원격 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-271">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-272">Apple App Store를 Google Play에서 iOS 및 Android용 Outlook 다운로드</span><span class="sxs-lookup"><span data-stu-id="b54c0-272">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-273">계정 구성 및 Exchange Online 사서함 액세스</span><span class="sxs-lookup"><span data-stu-id="b54c0-273">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-274">Outlook 모바일 보호(자세한 <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">내용은 Exchange Online의 iOS 및 Android 보안</a> 참조)</span><span class="sxs-lookup"><span data-stu-id="b54c0-274">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="b54c0-275">ID가 Office 365용 Azure AD에서 사용하도록 설정된 경우</span><span class="sxs-lookup"><span data-stu-id="b54c0-275">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-276">Exchange Online이 구성되고 라이선스가 할당됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-276">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b54c0-277"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-277"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-278">다음에 대한 원격 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-278">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-279">Power BI 라이선스를 할당합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-279">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-280">Power BI Desktop 앱을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-280">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="b54c0-281">Power BI Desktop과 같은 온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 및 Office의 시스템 요구 사항에 정의된 것처럼 최소 수준으로 설치되어야 합니다.</a></span><span class="sxs-lookup"><span data-stu-id="b54c0-281">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b54c0-282"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-282"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-283">다음에 대한 원격 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-283">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-284">Project Online이 사용하는 기본 SharePoint 기능 확인</span><span class="sxs-lookup"><span data-stu-id="b54c0-284">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-285">테넌트에 Project Online 서비스 추가(사용자에게 구독 추가 포함)</span><span class="sxs-lookup"><span data-stu-id="b54c0-285">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="b54c0-286">ERP(Enterprise 자원 그룹) 설정</span><span class="sxs-lookup"><span data-stu-id="b54c0-286">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="b54c0-287">첫 번째 프로젝트 만들기</span><span class="sxs-lookup"><span data-stu-id="b54c0-287">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="b54c0-288">Project for Office 365와 같은 온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 및 Office의 시스템 요구 사항에 정의된 것처럼 최소 수준이 되어야 합니다.</a></span><span class="sxs-lookup"><span data-stu-id="b54c0-288">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b54c0-289"><strong>Project Online Professional 및 Premium</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-289"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-290">다음에 대한 원격 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-290">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-291">배포 문제 해결</span><span class="sxs-lookup"><span data-stu-id="b54c0-291">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-292">Microsoft 365 관리 센터 및 Windows PowerShell을 사용하여 최종 사용자 라이선스 할당</span><span class="sxs-lookup"><span data-stu-id="b54c0-292">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-293">간편 실행을 사용하여 Office 365 포털에서 Project Online 데스크톱 클라이언트 설치</span><span class="sxs-lookup"><span data-stu-id="b54c0-293">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-294">Office 365 배포 도구를 사용하여 업데이트 설정 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-294">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-295">Project Online 데스크톱 클라이언트를 위한 단일 사이트에 배포 서버 설정(Office 365 배포 도구용 configuration.xml 파일을 만드는 지침 포함)</span><span class="sxs-lookup"><span data-stu-id="b54c0-295">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-296">Project Online 데스크톱 클라이언트을 Project Online Professional 또는 Project Online Premium에 연결합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-296">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="b54c0-297">Project for Office 365와 같은 온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 및 Office의 시스템 요구 사항에 정의된 것처럼 최소 수준이 되어야 합니다.</a></span><span class="sxs-lookup"><span data-stu-id="b54c0-297">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b54c0-298"><strong>SharePoint Online 및 비즈니스용 OneDrive</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-298"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-299">다음에 대한 원격 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-299">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-300">DNS 설정.</span><span class="sxs-lookup"><span data-stu-id="b54c0-300">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-301">방화벽 포트 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-301">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-302">사용자 및 라이선스 프로비전</span><span class="sxs-lookup"><span data-stu-id="b54c0-302">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="b54c0-303">SharePoint Online 관리자에 대해 사이트 만들기를 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="b54c0-303">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="b54c0-304">사이트 모음 계획</span><span class="sxs-lookup"><span data-stu-id="b54c0-304">Planning site collections.</span></span></li>
<li><span data-ttu-id="b54c0-305">콘텐츠 보호 및 권한 관리</span><span class="sxs-lookup"><span data-stu-id="b54c0-305">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="b54c0-306">SharePoint Online 기능 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-306">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="b54c0-307">하이브리드 검색, 하이브리드 사이트, 하이브리드 분류, 콘텐츠 형식, 하이브리드 셀프 서비스 사이트 만들기(SharePoint Server 2013 전용), 확장된 앱 시작 관리자, 하이브리드 비즈니스용 OneDrive, 익스트라넷 사이트 등의 SharePoint 하이브리드 기능을 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-307">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-308">마이그레이션에 대한 사용 방식</span><span class="sxs-lookup"><span data-stu-id="b54c0-308">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="b54c0-309">다음과 같이 SharePoint 버전에 따라 비즈니스용 OneDrive에 대한 추가 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-309">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-310">통합 옵션 식별 및 온-프레미스 및 온라인 네트워크 인프라와 대역폭 검토</span><span class="sxs-lookup"><span data-stu-id="b54c0-310">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-311">SharePoint Online 2013 SP1(해당되는 경우), 동기화 및 ID 요구 사항을 계획 및 구현하고, 비즈니스용 OneDrive 동기화 클라이언트 식별</span><span class="sxs-lookup"><span data-stu-id="b54c0-311">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-312">모든 사용자(또는 단계별 배포)에 대한 단일 롤아웃을 계획 및 구현합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-312">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="b54c0-313">라이선스를 할당하고, 내 사이트 및 개인 문서 라이브러리를 Office 365로 리디렉션(SharePoint Online 2013에 해당)하여 대상 그룹을 설정하여 OneDrive에 대한 액세스를 제어합니다(SharePoint Online 2013에 해당됨).</span><span class="sxs-lookup"><span data-stu-id="b54c0-313">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="b54c0-314">알려진 폴더를 OneDrive로 리디렉션 또는 이동</span><span class="sxs-lookup"><span data-stu-id="b54c0-314">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="b54c0-315">비즈니스용 OneDrive 클라이언트 동기화 배포</span><span class="sxs-lookup"><span data-stu-id="b54c0-315">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="b54c0-316">
  <strong>데이터 마이그레이션</strong>  </span><span class="sxs-lookup"><span data-stu-id="b54c0-316">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="b54c0-317">Office 365로의 데이터 마이그레이션에 대한 FastTrack 혜택을 사용하는 방법에 대한 자세한 내용은 데이터 <a href="https://review.docs.microsoft.com/fasttrack/data-migration">마이그레이션을 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="b54c0-317">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="b54c0-318"><strong>SharePoint 하이브리드의 경우:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="b54c0-318"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="b54c0-319">SharePoint 하이브리드 구성에는 온-프레미스에서 단일 대상 SharePoint Online 환경으로 연결된 하이브리드 검색, 사이트, 분류, 콘텐츠 형식, 비즈니스용 OneDrive, 확장된 앱 시작 관리자, 엑스트라넷 사이트 및 셀프 서비스 사이트 만들기 구성이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-319">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="b54c0-320">
  <strong>참고:</strong> 셀프 서비스 사이트 만들기는 SharePoint 2013을 실행하는 온-프레미스 서버에 포함되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-320">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="b54c0-321">SharePoint 하이브리드를 사용하려면 다음 온-프레미스 SharePoint Server 환경 중 하나: 2013, 2016 또는 2019가 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-321">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="b54c0-322">
  <strong>참고:</strong> 온-프레미스 SharePoint 환경을 SharePoint Server로 업그레이드하는 것은 범위 내에 있지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-322">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="b54c0-323">Microsoft <a href="https://go.microsoft.com/fwlink/?linkid=2080150">파트너에게</a> 도와문하십시오.</span><span class="sxs-lookup"><span data-stu-id="b54c0-323">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="b54c0-324">자세한 내용은 <a href="https://go.microsoft.com/fwlink/?linkid=853548">SharePoint 하이브리드 기능에 대한 최소 공개 업데이트 수준을 참조하세요.</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="b54c0-324">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="b54c0-325">
  <strong>참고:</strong> 다중 위치 기능에 대한 자세한 내용은 <a href="https://go.microsoft.com/fwlink/?linkid=831056">Office 365의 OneDrive 및 SharePoint Online의 다중 위치 기능을 참조하세요.</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="b54c0-325">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b54c0-326"><strong>비즈니스용 Skype Online</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-326"><strong>Skype for Business Online</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-327">다음에 대한 원격 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-327">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-328">방화벽 포트 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-328">Configuring firewall ports.</span></span>  </li>

<li>  <span data-ttu-id="b54c0-329">DNS 설정.</span><span class="sxs-lookup"><span data-stu-id="b54c0-329">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-330">네트워크 평가:</span><span class="sxs-lookup"><span data-stu-id="b54c0-330">Network assessment:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-331">포트 및 끝점 검사</span><span class="sxs-lookup"><span data-stu-id="b54c0-331">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-332">연결 품질 검사</span><span class="sxs-lookup"><span data-stu-id="b54c0-332">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-333">대역폭 예상</span><span class="sxs-lookup"><span data-stu-id="b54c0-333">Bandwidth estimates.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="b54c0-334">채팅방 시스템 장치용 계정 만들기</span><span class="sxs-lookup"><span data-stu-id="b54c0-334">Creating accounts for any room system devices.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-335">지원되는 비즈니스용 Skype 온라인 클라이언트 배포</span><span class="sxs-lookup"><span data-stu-id="b54c0-335">Deploying a supported Skype for Business Online client.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-336">온-프레미스 Lync 2010, Lync 2013 또는 비즈니스용 Skype 2015 서버 환경 및 비즈니스용 Skype 온라인 테넌트(해당하는 경우), 통화 계획, Skype 모임 브로드캐스트, 전화 시스템 및 통화 계획(사용 가능한 시장) 간에 분할 도메인 서버 구성을 설정합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-336">Establishing split domain server configuration between your on-premises Lync 2010, Lync 2013, or Skype for Business 2015 server environment and Skype for Business Online tenant (if applicable), Calling Plans, Skype Meeting Broadcast, and Phone System and Calling Plans (in available markets).</span></span>  
  <span data-ttu-id="b54c0-337">해당하는 경우 FastTrack은 다음을 안내합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-337">If applicable, FastTrack also guides you through:</span></span>  </li>
<li>  <span data-ttu-id="b54c0-338">회의실 시스템 장치 구성:</span><span class="sxs-lookup"><span data-stu-id="b54c0-338">Configuring room system device:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-339">비즈니스용 Skype 솔루션 카탈로그의 회의실 시스템에 나열된 지원되는 회의실 장치에 <a href="https://go.microsoft.com/fwlink/?LinkId=615775">필요한 온라인 계정을 만듭니다.</a></span><span class="sxs-lookup"><span data-stu-id="b54c0-339">Creation of online accounts needed for supported conference room devices listed on the Meeting Room Systems tab in the <a href="https://go.microsoft.com/fwlink/?LinkId=615775">Skype for Business solutions catalog</a>.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="b54c0-340">하이브리드 및 분할된 도메인 서버 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-340">Configuring hybrid and split domain servers.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-341">오디오 회의 구성:</span><span class="sxs-lookup"><span data-stu-id="b54c0-341">Configuring Audio Conferencing:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-342">회의 브리지 기본 설정에 대한 조직 설정</span><span class="sxs-lookup"><span data-stu-id="b54c0-342">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-343">회의 브리지를 라이선스가 있는 사용자에게 할당</span><span class="sxs-lookup"><span data-stu-id="b54c0-343">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="b54c0-344">전화 시스템 기본 설정 구성:</span><span class="sxs-lookup"><span data-stu-id="b54c0-344">Configuring Phone System default settings:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-345">통화 플랜:</span><span class="sxs-lookup"><span data-stu-id="b54c0-345">Calling Plans:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-346">사용자에게 번호 할당</span><span class="sxs-lookup"><span data-stu-id="b54c0-346">Assignment of numbers to licenses users.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-347">사용자 인터페이스를 통해 최대 99개까지의 지역 번호 이식 지침</span><span class="sxs-lookup"><span data-stu-id="b54c0-347">Local number porting guidance through user interface up to 99</span></span>  </li>
<li>  <span data-ttu-id="b54c0-348">999개가 초과하는 지역 번호 이식 서비스 요청 지원</span><span class="sxs-lookup"><span data-stu-id="b54c0-348">Local number porting service request support over 999</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="b54c0-349">비즈니스용 Skype 모임 브로드캐스트 구성:</span><span class="sxs-lookup"><span data-stu-id="b54c0-349">Configure Skype for Business Meeting Broadcast:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-350">모임 브로드캐스트 서비스가 있는 페더레이션에 대한 조직 설정</span><span class="sxs-lookup"><span data-stu-id="b54c0-350">Organization setup for federation with Meeting Broadcast service.</span></span>  </li>
</ul></li>
</ul></td>
<td>  <span data-ttu-id="b54c0-351"><strong>Lync 하이브리드의 경우:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="b54c0-351"><strong>For Lync hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="b54c0-352">단일 온-프레미스 Active Directory 포리스트</span><span class="sxs-lookup"><span data-stu-id="b54c0-352">A single on-premises Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-353">Lync 2013 관리 도구 또는 비즈니스용 Skype 2015 관리 도구가 있는 Lync 2010 서버 환경 및 Lync 2010 에지 서버 역할</span><span class="sxs-lookup"><span data-stu-id="b54c0-353">A Lync 2010 Server environment with Lync 2013 admin tools or Skype for Business 2015 admin tools and a Lync 2010 edge server role.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-354">Lync 2013 서버 환경 및 Lync 2013 에지 서버 역할</span><span class="sxs-lookup"><span data-stu-id="b54c0-354">A Lync 2013 Server environment and a Lync 2013 edge server role.</span></span>  </li>
</ul><span data-ttu-id="b54c0-355">
  <strong>비즈니스용 Skype 하이브리드:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="b54c0-355">
  <strong>For Skype for Business hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="b54c0-356">단일 온-프레미스 Active Directory 포리스트</span><span class="sxs-lookup"><span data-stu-id="b54c0-356">A single on-premises Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-357">단일 Active Directory 계정 포리스트 이상 및 리소스 포리스트(Exchange 및/또는 비즈니스용 Skype) 토폴로지</span><span class="sxs-lookup"><span data-stu-id="b54c0-357">A single Active Directory account forest onward and resource forest (Exchange and/or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-358">Exchange 및/또는 비즈니스용 Skype에 중앙 집중식 Active Directory 계정 포리스트 하나가 포함된 여러 Active Directory 계정 포리스트</span><span class="sxs-lookup"><span data-stu-id="b54c0-358">Multiple Active Directory account forests, with one forest being a centralized Active Directory account forest with Exchange and/or Skype for Business in it.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-359">비즈니스용 Skype 에지 서버 역할을 포함하는 비즈니스용 Skype Server 2015 환경</span><span class="sxs-lookup"><span data-stu-id="b54c0-359">A Skype for Business Server 2015 environment including a Skype for Business edge server role.</span></span>  </li>
</ul><span data-ttu-id="b54c0-360">
  <strong>참고:</strong> 이 추가 서비스는 분할 도메인(하이브리드) 작업의 구성 및 유효성 검사용이고, 온-프레미스 구성 요소(예: Lync 2013 관리 도구 또는 Lync 2013/비즈니스용 Skype 온라인 서버 또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype 에지 서버) 도입을 포함하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-360">
  <strong>Note:</strong> This additional service is for configuring and validating of the split domain (hybrid) tasks and doesn't include introducing on-premises components (for example, Lync 2013 admin tools or Lync 2013/Skype for Business Online servers, or Lync 2010, Lync 2013, or Skype for Business edge servers).</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="b54c0-361"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-361"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="b54c0-362">Microsoft에서는 엔터프라이즈 서비스를 사용하도록 설정하는 데 에디하며 Yammer 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-362">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="b54c0-363">온라인 클라이언트 소프트웨어는 Microsoft 365 및 Office의 시스템 요구 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">사항에 정의된 적어도 수준으로 있어야 합니다.</a></span><span class="sxs-lookup"><span data-stu-id="b54c0-363">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="b54c0-364">Enterprise Mobility & 보안</span><span class="sxs-lookup"><span data-stu-id="b54c0-364">Enterprise Mobility & Security</span></span>

<table>
<thead>
</tr>
<tr class="even">
<td><span data-ttu-id="b54c0-365"><strong>Azure AD(Azure Active Directory) 및 Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-365"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-366">다음 시나리오에 대한 클라우드 ID 보안을 위해 원격 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-366">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="b54c0-367">

<strong>Secure Foundation 인프라</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="b54c0-367">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="b54c0-368">Azure MFA(Multi-Factor Authentication)(클라우드 전용), Microsoft Authenticator 앱, Azure MFA 및 SSPR(셀프 서비스 암호 재설정)에 대한 결합을 포함하여 ID에 대한 강력한 인증 구성 및 사용.</span><span class="sxs-lookup"><span data-stu-id="b54c0-368">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="b54c0-369">Azure AD Premium이 아닌 고객의 경우 보안 기본값을 사용하여 ID를 보호하기 위한 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-369">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-370">Azure AD Premium 고객의 경우 조건부 액세스로 ID를 보호하기 위한 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-370">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-371">Azure AD 암호 보호에서 약한 암호의 사용을 감지하고 차단</span><span class="sxs-lookup"><span data-stu-id="b54c0-371">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-372">Azure AD 응용 프로그램 프록시를 사용하여 온-프레미스 웹앱에 대한 원격 액세스 보안</span><span class="sxs-lookup"><span data-stu-id="b54c0-372">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-373">Azure ID 보호를 사용하여 위험 기반 검색 및 업데이트 관리 사용</span><span class="sxs-lookup"><span data-stu-id="b54c0-373">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-374">사용자 지정 브랜딩으로 로고, 텍스트 및 이미지를 포함한 사용자 지정된 로그인 화면을 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="b54c0-374">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-375">Azure AD B2B를 사용하여 게스트 사용자와 앱 및 서비스를 안전하게 공유합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-375">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-376">RBAC(역할 기반 액세스 제어) 기본 제공 관리 역할을 사용하여 Office 365 관리자의 액세스 권한을 관리하고 권한 있는 관리자 계정의 수를 줄입니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-376">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-377">하이브리드 Azure AD 조인을 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-377">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-378">Azure AD 조인을 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-378">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="b54c0-379">
  
<strong>모니터링 및 보고</strong>  
</span><span class="sxs-lookup"><span data-stu-id="b54c0-379">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="b54c0-380">Azure AD Connect Health로 AD FS, Azure AD Connect 및 도메인 컨트롤러에 대한 원격 모니터링을 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="b54c0-380">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="b54c0-381">
  
<strong>거버넌스</strong>  
</span><span class="sxs-lookup"><span data-stu-id="b54c0-381">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="b54c0-382">Azure AD 권한 관리를 사용하여 Azure AD ID 및 액세스 수명 주기를 관리합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-382">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="b54c0-383">Azure AD 액세스 검토를 사용하여 Azure AD 그룹 구성원 자격, 엔터프라이즈 앱 액세스 및 역할 할당을 관리합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-383">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-384">Azure 의사용 약관 검토</span><span class="sxs-lookup"><span data-stu-id="b54c0-384">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-385">Azure AD Privileged Identity Management를 사용하여 권한 있는 관리자 계정에 대한 액세스 관리 및 제어</span><span class="sxs-lookup"><span data-stu-id="b54c0-385">Managing and controling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="b54c0-386">
  
<strong>자동화 및 효율성 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="b54c0-386">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="b54c0-387">Azure AD SSPR을 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="b54c0-387">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="b54c0-388">Azure AD 셀프 서비스 그룹 관리를 통해 사용자가 자신의 클라우드 보안 또는 Office 365 그룹을 만들고 관리할 수 있도록 허용합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-388">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-389">Azure AD 위임 그룹 관리를 사용하여 엔터프라이즈 앱에 대한 위임된 액세스 관리</span><span class="sxs-lookup"><span data-stu-id="b54c0-389">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-390">Azure AD 동적 그룹 사용</span><span class="sxs-lookup"><span data-stu-id="b54c0-390">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-391">컬렉션을 사용하여 내 앱 포털에서 앱 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-391">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="b54c0-392">Azure AD 및 Azure AD Premium 기능과의 통합을 방지하는 식별된 문제를 수정하기 위해 온-프레미스 Active Directory와 해당 환경이 Azure AD Premium용으로 준비되었습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-392">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b54c0-393"><strong>Azure Information Protection(P2 또는 EMS E5)</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-393"><strong>Azure Information Protection (P2 or EMS E5)</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-394">다음 작업 방법을 안내합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-394">We provide guidance on how to:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-395">테넌트를 활성화하고 구성하기</span><span class="sxs-lookup"><span data-stu-id="b54c0-395">Activate and configure your tenant.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-396">레이블과 정책을 만들고 설정하기</span><span class="sxs-lookup"><span data-stu-id="b54c0-396">Create and set up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-397">문서에 정보 보호 적용하기</span><span class="sxs-lookup"><span data-stu-id="b54c0-397">Apply information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-398">Azure Information Protection 클라이언트를 사용하여 Windows에서 실행 중인 Office 앱(Word, PowerPoint, Excel, Outlook 등)에서 자동으로 정보 분류 및 레이블 지정하기</span><span class="sxs-lookup"><span data-stu-id="b54c0-398">Automatically classify and label information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-399">Azure Information Protection 스캐너를 사용하여 보관 중인 파일 사용하기</span><span class="sxs-lookup"><span data-stu-id="b54c0-399">Use files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-400">Exchange Online 메일 흐름 규칙을 사용하여 전송 중인 전자 메일 모니터링하기</span><span class="sxs-lookup"><span data-stu-id="b54c0-400">Monitor emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="b54c0-401">Microsoft Azure RMS(권한 관리 서비스), OME(Office 365 메시지 암호화) 및 DLP(데이터 손실 방지)를 사용하여 보호를 적용하려는 경우 지침도 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-401">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="b54c0-402">다음과 같은 설정이 구성되어 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-402">You should already:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-403">Azure AD 사용.</span><span class="sxs-lookup"><span data-stu-id="b54c0-403">Use Azure AD.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-404">Windows 또는 iOS(다른 운영 체제는 다되지 않음) 사용</span><span class="sxs-lookup"><span data-stu-id="b54c0-404">Use either Windows or iOS (other operating systems are out of scope).</span></span>  
  </ul><span data-ttu-id="b54c0-405">
<strong>참고:</strong>컴퓨터 및 모바일 디바이스는 Azure Information <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">Protection을 지원하는 운영</a> 체제에서 실행해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-405">
<strong>Note</strong>: Computers and mobile devices must run on an <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">operating system</a> that supports Azure Information Protection.</span></span>  
<li>  <span data-ttu-id="b54c0-406">주 파일 공유 위치 보세요.</span><span class="sxs-lookup"><span data-stu-id="b54c0-406">Have your main file share locations.</span></span>  </li><span data-ttu-id="b54c0-407">
<strong>참고</strong>: 하이브리드 지원을 사용하려면 AD RMS 커넥터가 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-407">
<strong>Note</strong>: Hybrid support requires the AD RMS connector.</span></span> 
<li>  <span data-ttu-id="b54c0-408">승인된 분류체계 보수</span><span class="sxs-lookup"><span data-stu-id="b54c0-408">Have an approved classification taxonomy.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-409">보호되는 키 관리에 대한 어법 제한사항을 이해합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-409">Understand any regulatory restrictions for your protected key management.</span></span>  </li><span data-ttu-id="b54c0-410">
</ul>
  
<strong>Azure Information Protection 스캐너</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-410">
</ul>
  
<strong>Azure Information Protection scanner</strong></span></span>  
  
<span data-ttu-id="b54c0-411">다음과 같은 설정이 구성되어 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-411">You should already:</span></span>  
<ul>
<li>  <span data-ttu-id="b54c0-412">설치 관리자 Windows Server 2012 R2 또는 Windows Server 2016을 사용합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-412">Use Windows Server 2012 R2 or Windows Server 2016.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-413">인터넷 연결</span><span class="sxs-lookup"><span data-stu-id="b54c0-413">Have an internet connection.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-414">로컬 Microsoft SQL Server 원격 인스턴스에서 2012 이상을 배포해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-414">Have Microsoft SQL Server 2012 onward in a local or remote instance.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-415">온-프레미스 Active Directory에 대해 만들고 Azure AD와 동기화하는 서비스 계정을 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-415">Have a service account created for your on-premises Active Directory and synchronized with Azure AD.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-416">다운로드한 AzInfoProtection.exe.</span><span class="sxs-lookup"><span data-stu-id="b54c0-416">Have downloaded AzInfoProtection.exe.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-417">자동 분류/보호에 대한 레이블을 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-417">Have labels configured for Automatic Classification/Protection.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b54c0-418"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-418"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-419">앱 및 장치용 클라우드 기반 MDM(모바일 장치 관리) 및 MAM(모바일 앱 관리) 공급자로 Intune을 사용하기 위한 준비에 대한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-419">We provide guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="b54c0-420">정확한 단계는 원본 환경에 따라 다르며 모바일 장치와 모바일 앱 관리 요구 사항에 기반합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-420">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="b54c0-421">해당 단계는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-421">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-422">최종 사용자에게 라이선스 부여</span><span class="sxs-lookup"><span data-stu-id="b54c0-422">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-423">온-프레미스 Active Directory 또는 클라우드 ID(Azure AD)를 이용하여 Intune에서 사용할 ID 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-423">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="b54c0-424">Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기</span><span class="sxs-lookup"><span data-stu-id="b54c0-424">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-425">다음과 같은 관리 요구 사항에 따라 MDM 기관 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-425">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-426">Intune이 유일한 MDM 솔루션인 경우 Intune을 MDM 기관으로 설정</span><span class="sxs-lookup"><span data-stu-id="b54c0-426">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="b54c0-427">MDM 지침 제공:</span><span class="sxs-lookup"><span data-stu-id="b54c0-427">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-428">MDM 관리 정책의 유효성을 검사하는 데 사용할 테스트 그룹 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-428">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-429">다음과 같은 MDM 관리 정책 및 서비스 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-429">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-430">웹 링크 또는 전체 링크를 통해 지원되는 각 플랫폼용 앱 배포</span><span class="sxs-lookup"><span data-stu-id="b54c0-430">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-431">조건부 액세스 정책.</span><span class="sxs-lookup"><span data-stu-id="b54c0-431">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-432">조직에서 기존 인증 기관, 무선 네트워크 또는 VPN 인프라를 보유하고 있는 경우 전자 메일, 무선 네트워크, VPN) 프로필 배포</span><span class="sxs-lookup"><span data-stu-id="b54c0-432">Deployment of email, wireless networks, and VPN)profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-433">Microsoft Intune Exchange Connector 설정(해당하는 경우)</span><span class="sxs-lookup"><span data-stu-id="b54c0-433">Setting up the Microsoft Intune Exchange Connector (when applicable).</span></span>  </li>
<li>  <span data-ttu-id="b54c0-434">Intune 데이터 웨어하우스에 연결</span><span class="sxs-lookup"><span data-stu-id="b54c0-434">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-435">다음에 Intune 통합:</span><span class="sxs-lookup"><span data-stu-id="b54c0-435">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-436">원격 지원을 위한 팀 뷰어(팀 뷰어 구독 필수)</span><span class="sxs-lookup"><span data-stu-id="b54c0-436">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="b54c0-437">MTD(Mobile Threat Defense) 파트너 솔루션(MTD 구독 필수)</span><span class="sxs-lookup"><span data-stu-id="b54c0-437">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="b54c0-438">Telecom Expense Management 솔루션(Telecom Expense Management 구독 필수)</span><span class="sxs-lookup"><span data-stu-id="b54c0-438">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="b54c0-439">Microsoft Defender ATP(Windows E5 또는 Microsoft 365 E5 라이선스 필요)</span><span class="sxs-lookup"><span data-stu-id="b54c0-439">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="b54c0-440">각 지원되는 플랫폼의 장치를 Intune에 등록합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-440">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="b54c0-441">앱 보호 지침 제공:</span><span class="sxs-lookup"><span data-stu-id="b54c0-441">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-442">지원되는 각 플랫폼에 대한 Intune 앱 보호 정책 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-442">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-443">관리되는 앱에 대한 조건부 액세스 정책 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-443">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-444">이전에 언급한 MAM 정책을 사용하여 적절한 사용자 그룹을 대상으로 지정</span><span class="sxs-lookup"><span data-stu-id="b54c0-444">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-445">관리 앱 사용 현황 보고서 사용</span><span class="sxs-lookup"><span data-stu-id="b54c0-445">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="b54c0-446">레거시 PC 관리에서 Intune MDM에 마이그레이션 지침 제공</span><span class="sxs-lookup"><span data-stu-id="b54c0-446">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="b54c0-447">
  <strong>참고</strong>: 2020년 10월 15일 이후로부터 는 레거시 PC 관리가 더 이상 지원되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-447">
  <strong>Note</strong>: Legacy PC management is no longer supported from October 15, 2020 onward.</span></span>  
<span data-ttu-id="b54c0-448"></li>
</ul>
  
<strong>클라우드 연결</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-448"></li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="b54c0-449">Intune을 사용하여 기존의 Configuration Manager 환경을 클라우드 연결하기 위한 준비를 안내합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-449">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="b54c0-450">정확한 단계는 원본 환경에 따라 다릅니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-450">The exact steps depend on your source environment.</span></span> <span data-ttu-id="b54c0-451">해당 단계는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-451">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="b54c0-452">Intune을 사용하여 클라우드에 연결하는 방법에 대해 설명합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-452">Explaining the benefits of cloud-attaching Configuration Manager with Intune.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-453">최종 사용자에게 라이선스 부여</span><span class="sxs-lookup"><span data-stu-id="b54c0-453">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-454">온-프레미스 Active Directory 및 클라우드 ID를 활용하여 Intune에서 사용할 ID 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-454">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-455">Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기</span><span class="sxs-lookup"><span data-stu-id="b54c0-455">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-456">Configuration Manager 콘솔에서 클라우드 연결을 사용하도록 설정합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-456">Enabling cloud-attach in the Configuration Manager console.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-457">하이브리드 Azure AD 조인설정에 대한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-457">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-458">MDM 자동 등록을 위해 Azure AD 설정하는 것에 대한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-458">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-459">클라우드 관리 게이트웨이를 설정하는 방법에 대한 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-459">Providing guidance on how to set up cloud management gateway.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-460">Intune으로 전환할 지원되는 작업 부하를 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-460">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-461">Intune에서 등록된 디바이스에서 Configuration Manager 클라이언트를 설치합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-461">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="b54c0-462"><strong>iOS 및 Android용 Outlook 모바일을 안전하게 배포</strong> 사용자가 필요한 모든 앱을 설치하도록 조직에서 iOS 및 Android용 Outlook 모바일을 안전하게 배포하는 데 도움이 되는 지침을 제공할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-462"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="b54c0-463">Intune을 사용하여 iOS 및 Android용 Outlook 모바일을 안전하게 배포하는 단계는 원본 환경에 따라 다릅니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-463">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="b54c0-464">다음과 같이 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-464">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-465">Apple App Store 또는 Google Play 스토어를 통해 iOS 및 Android용 Outlook, Microsoft Authenticator 및 Intune Company Portal 앱 다운로드</span><span class="sxs-lookup"><span data-stu-id="b54c0-465">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-466">설정에 대한 지침 제공:</span><span class="sxs-lookup"><span data-stu-id="b54c0-466">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-467">Intune을 사용한 iOS 및 Android용 Outlook, Microsoft Authenticator 및 Intune Company Portal 앱 배포</span><span class="sxs-lookup"><span data-stu-id="b54c0-467">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-468">앱 보호 정책.</span><span class="sxs-lookup"><span data-stu-id="b54c0-468">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-469">조건부 액세스 정책.</span><span class="sxs-lookup"><span data-stu-id="b54c0-469">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-470">앱 구성 정책.</span><span class="sxs-lookup"><span data-stu-id="b54c0-470">App configuration policies.</span></span>  </li>
</ul></li>
</ul>
  
  <span data-ttu-id="b54c0-471"><strong>참고:</strong>FastTrack은 Exchange 모바일 장치 사서함 정책을 사용하여 iOS 및 Android용 Outlook 보안을 지원하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-471"><strong>Note</strong>: FastTrack doesn’t support securing Outlook for iOS and Android with Exchange mobile device mailbox policies.</span></span> <span data-ttu-id="b54c0-472">이에 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">대한 지원을</a> 받기만 하면 Microsoft 파트너에 문의하세요.</span><span class="sxs-lookup"><span data-stu-id="b54c0-472">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  </td>
<td>  <span data-ttu-id="b54c0-473">IT 관리자는 Intune에서 무선 네트워크 및 VPN 프로필 배포를 계획할 때 기존 인증 기관, 무선 네트워크 및 VPN 인프라를 프로덕션 환경에서 이미 사용하고 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-473">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="b54c0-474"><strong>참고:</strong>Intune에 대한 인증 기관, 무선 네트워크, VPN 인프라 또는 Apple MDM 푸시 인증서를 설정 또는 구성하기 위한 지원은 FastTrack 서비스 혜택에 포함되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-474"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  

<span data-ttu-id="b54c0-475"><strong>Intune을 사용하여 Configuration Manager를 클라우드에 연결</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-475"><strong>Cloud-attach Configuration Manager with Intune</strong></span></span>  

 <span data-ttu-id="b54c0-476">클라우드 연결 기능을 사용하여 IT 관리자는 온-프레미스 환경을 준비해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-476">With cloud-attach, IT admins are responsible for preparing the on-premises environment.</span></span> <span data-ttu-id="b54c0-477">여기에는 Configuration Manager 환경을 Intune과 클라우드에 연결하지 못하도록 방지하는 문제의 수정이 포함될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-477">This can include remediation of issues that prevent you from cloud-attaching your Configuration Manager environments with Intune.</span></span>  
  <span data-ttu-id="b54c0-478"><strong>참고</strong>: 클라우드 연결 기능을 지원하는 데 필요한 최소 요구 사항에 맞게 Configuration Manager 사이트 서버 또는 Configuration Manager 클라이언트를 설정하거나 업그레이드하기 위한 지원은 FastTrack 서비스 혜택에 포함되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-478"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="b54c0-479">이에 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">대한 지원을</a> 받기만 하면 Microsoft 파트너에 문의하세요.</span><span class="sxs-lookup"><span data-stu-id="b54c0-479">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="b54c0-480"><strong>Microsoft Defender ATP(Advanced Threat Protection)에 통합된 Intune</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-480"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="b54c0-481"><strong>참고:</strong>Intune과 Microsoft Defender ATP를 통합하고 Windows 10 위험 수준 평가에 따라 장치 준수 정책을 만들기 위한 지원을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-481"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="b54c0-482">구입, 라이선스 또는 정품 인증에 대한 지원은 제공하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-482">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="b54c0-483">이에 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">대한 지원을</a> 받기만 하면 Microsoft 파트너에 문의하세요.</span><span class="sxs-lookup"><span data-stu-id="b54c0-483">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="b54c0-484"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-484"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="b54c0-485">IT 관리자는 하드웨어 공급 업체가 사용자를 대신하여 하드웨어 ID를 업로드하거나 Windows Autopilot 서비스로 업로드하는 방법으로 조직에 장치를 등록합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-485">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
<span data-ttu-id="b54c0-486"><strong>Intune을 사용하여 iOS 및 Android용 Outlook을 안전하게 배포 </strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-486"><strong>Deploy Outlook for iOS and Android securely with Intune </strong></span></span>  
<ul>
<li>  <span data-ttu-id="b54c0-487">Office 365용 Azure AD에서 사용자 ID사용.</span><span class="sxs-lookup"><span data-stu-id="b54c0-487">User identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-488">사용자 라이선스를 할당하여 구성된 Exchange Online 또는 하이브리드 Exchange</span><span class="sxs-lookup"><span data-stu-id="b54c0-488">Exchange Online or hybrid Exchange configured with user licenses assigned.</span></span>  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="b54c0-489">Windows 10</span><span class="sxs-lookup"><span data-stu-id="b54c0-489">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="b54c0-490"><strong>서비스</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-490"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="b54c0-491"><strong>FastTrack 지침 세부 정보</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-491"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="b54c0-492"><strong>원본 환경 기대</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-492"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b54c0-493"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-493"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-494">Windows 7 Professional 및 Windows 8.1 Professional에서 Windows 10 Enterprise로 업그레이드하는 데 도움이 되는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-494">We provide guidance to help you upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="b54c0-495">다음에 대한 원격 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-495">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-496">Windows 10 의도 이해</span><span class="sxs-lookup"><span data-stu-id="b54c0-496">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-497">원본 환경 및 요구 사항 평가(Microsoft Endpoint Configuration Manager가 Windows 10 배포를 지원하는 데 필요한 수준으로 업그레이드되는지 확인)</span><span class="sxs-lookup"><span data-stu-id="b54c0-497">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="b54c0-498">Microsoft Endpoint Configuration Manager 또는 Microsoft 365를 사용하여 Windows 10 Enterprise 및 Microsoft 365 앱을 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-498">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-499">Windows 10 앱을 평가하는 데 권장 옵션이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-499">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-500">Desktop Analytics 배포 계획 만들기를 통해 Desktop Analytics 및 지침 사용</span><span class="sxs-lookup"><span data-stu-id="b54c0-500">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-501">Configuration Manager에서 Office 365 준비 상태 대시보드를 사용하거나 Office에 Office 365 앱을 배포하는 데 도움을 주기 위한 독립형 준비 Toolkit 사용하여 Microsoft 365 앱 호환성 평가.</span><span class="sxs-lookup"><span data-stu-id="b54c0-501">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-502">Microsoft Intune을 사용하여 클라우드 연결 구성 관리자를 포함 또는 단독 클라우드 관리 솔루션으로서 Intune을 배포하는 등의 최신 관리 전략을 평가합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-502">Assessing your modern management strategies, including cloud-attaching Configuration Manager with Microsoft Intune or deploying Intune as the sole cloud management solution.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-503">원본 환경을 성공적인 배포에 필요한 최소 요구 사항에 따라 수행할 작업에 대한 재구성 검사 목록을 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-503">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-504">기존 장치가 필요한 장치 하드웨어 요구 사항을 충족하는 경우 기존 장치를 Windows 10 Enterprise에 대한 업그레이드 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-504">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-505">기존 배포 동작을 지원하기 위한 업그레이드 지침 제공</span><span class="sxs-lookup"><span data-stu-id="b54c0-505">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="b54c0-506">FastTrack은 Windows 10으로의 준비된 업그레이드를 위한 지침을 권장하고 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-506">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="b54c0-507">Windows 정리 이미지 설치 및 Windows Autopilot 배포 시나리오에서도 지침을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-507">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-508">Windows 10 배포의 일부로 Configuration Manager를 사용하여 Microsoft 365 앱을 배포.</span><span class="sxs-lookup"><span data-stu-id="b54c0-508">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="b54c0-509">조직에서 기존 Configuration Manager 환경 또는 Microsoft 365를 사용하여 Windows 10 Enterprise 및 Microsoft 365 앱을 최신 상태로 유지할 수 있는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-509">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-510">클라우드 구성 관리자를 Intune에 설치하거나 Intune 독립 실행형(필수)을 배포하여 최신 관리를 활성화하는 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-510">Providing guidance to enable modern management by cloud-attaching Configuration Manager to Intune or by deploying Intune standalone (where required).</span></span>  </li>
</ul><span data-ttu-id="b54c0-511">
  <strong>다음 범위를 벗어나는 경우 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="b54c0-511">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="b54c0-512">Configuration Manager를 현재 분기로 업그레이드.</span><span class="sxs-lookup"><span data-stu-id="b54c0-512">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-513">Windows 10 배포용 사용자 지정 이미지 만들기.</span><span class="sxs-lookup"><span data-stu-id="b54c0-513">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-514">Windows 10 배포용 배포 스크립트 만들기 및 지원</span><span class="sxs-lookup"><span data-stu-id="b54c0-514">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-515">Windows 10 시스템을 BIOS에서 UEFI(Unified Extensible Firmware Interface)로 변환.</span><span class="sxs-lookup"><span data-stu-id="b54c0-515">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="b54c0-516">Windows 10 보안 기능 활성화.</span><span class="sxs-lookup"><span data-stu-id="b54c0-516">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-517">PXE(Preboot Execution Environment) 부팅을 위해 WDS(Windows Deployment Services) 구성.</span><span class="sxs-lookup"><span data-stu-id="b54c0-517">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-518">Windows 10 이미지를 캡처하여 배포하는 데 MDT(Microsoft Deployment Toolkit) 사용.</span><span class="sxs-lookup"><span data-stu-id="b54c0-518">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-519">USMT(User State Migration Tool) 사용.</span><span class="sxs-lookup"><span data-stu-id="b54c0-519">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="b54c0-520">이러한 서비스에 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">대한 지원을</a> 받기 만드리고 Microsoft 파트너에게 문의하세요.</span><span class="sxs-lookup"><span data-stu-id="b54c0-520">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="b54c0-521">PC 업그레이드의 경우, 다음 요구 사항을 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-521">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-522">원본 OS: Windows 7 Enterprise 또는 Professional, Windows 8.1 Enterprise 또는 Professional</span><span class="sxs-lookup"><span data-stu-id="b54c0-522">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-523">장치: 데스크톱, 노트북 또는 태블릿 폼 팩터</span><span class="sxs-lookup"><span data-stu-id="b54c0-523">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-524">대상 OS: Window 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="b54c0-524">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="b54c0-525">인프라 업그레이드의 경우, 다음 요구 사항을 충족해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-525">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-526">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="b54c0-526">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-527">Configuration Manager 버전은 Windows 10 대상 버전에서 지원해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-527">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="b54c0-528">자세한 내용은 Configuration Manager에서 Windows 10 지원 시 Configuration <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Manager 지원 테이블을 참조하세요.</a></span><span class="sxs-lookup"><span data-stu-id="b54c0-528">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="b54c0-529"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="b54c0-529"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="b54c0-530">Microsoft Defender Advanced Threat Protection (ATP)는 엔터프라이즈 네트워크가 고급 위협을 방지, 탐지, 조사 및 대응하는 데 도움이 되도록 설계된 플랫폼입니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-530">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="b54c0-531">다음에 대한 원격 지침이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-531">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="b54c0-532">끝점을 안전하게 보호하기 위한 기술 배포</span><span class="sxs-lookup"><span data-stu-id="b54c0-532">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-533">엔드포인트 보호 및 장치 제한 프로필 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-533">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-534">OS 버전 및 장치 관리(Intune, Microsoft Endpoint Configuration Manager, GPO(그룹 정책 개체) 및 타사 구성 포함)과 Windows Defender AV 서비스 또는 기타 끝점 보안 소프트웨어의 상태를 평가하는 작업</span><span class="sxs-lookup"><span data-stu-id="b54c0-534">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-535">Windows AV 서비스 또는 기타 엔드포인트 보안 소프트웨어의 상태 평가.</span><span class="sxs-lookup"><span data-stu-id="b54c0-535">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-536">네트워크 트래픽을 제한하는 프록시 및 방화벽 평가.</span><span class="sxs-lookup"><span data-stu-id="b54c0-536">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-537">온보드 엔드포인트를 사용하여 ATP 에이전트 프로필을 배포하는 방법을 설명하여 Microsoft Defender ATP 서비스를 사용하도록 설정</span><span class="sxs-lookup"><span data-stu-id="b54c0-537">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-538">배포 지침, 구성 지원 및 교육:</span><span class="sxs-lookup"><span data-stu-id="b54c0-538">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="b54c0-539">위협 및 취약성 관리.</span><span class="sxs-lookup"><span data-stu-id="b54c0-539">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-540">공격 표면 감소.</span><span class="sxs-lookup"><span data-stu-id="b54c0-540">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-541">차세대 보호.</span><span class="sxs-lookup"><span data-stu-id="b54c0-541">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-542">끝점 감지 및 대응.</span><span class="sxs-lookup"><span data-stu-id="b54c0-542">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-543">자동화된 조사 및 조치.</span><span class="sxs-lookup"><span data-stu-id="b54c0-543">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-544">보안 점수.</span><span class="sxs-lookup"><span data-stu-id="b54c0-544">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="b54c0-545">시뮬레이션 및 자습서(연습 시나리오, 가까운 맬웨어 및 자동화된 조사) 검토</span><span class="sxs-lookup"><span data-stu-id="b54c0-545">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="b54c0-546">보고 및 위협 분석 기능에 대한 개요입니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-546">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-547">Office 365 ATP와 Microsoft Defender ATP 통합.</span><span class="sxs-lookup"><span data-stu-id="b54c0-547">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-548">Microsoft Defender 보안 센터 포털 탐색.</span><span class="sxs-lookup"><span data-stu-id="b54c0-548">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-549">다음 운영 체제</span><span class="sxs-lookup"><span data-stu-id="b54c0-549">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="b54c0-550">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="b54c0-550">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-551">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="b54c0-551">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-552">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="b54c0-552">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-553">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="b54c0-553">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-554">Windows Server SAC(반기 채널) 버전 1803.</span><span class="sxs-lookup"><span data-stu-id="b54c0-554">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-555">macOS 버전 10.13, 10.14 및 10.15.</span><span class="sxs-lookup"><span data-stu-id="b54c0-555">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="b54c0-556">
<strong>참고:</strong> 모든 Windows Server 버전은 최신 버전의 System Center Configuration Manager 2012(버전 1012 R2, 1511 또는 1602)나 Microsoft Endpoint Configuration Manager(버전 2002 이상)를 통해 관리해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="b54c0-556">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="b54c0-557"></li>
</ul>

<strong>다음 범위를 벗어나는 경우 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="b54c0-557"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="b54c0-558">고객의 수정 활동에 대한 프로젝트 관리.</span><span class="sxs-lookup"><span data-stu-id="b54c0-558">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-559">현장 지원.</span><span class="sxs-lookup"><span data-stu-id="b54c0-559">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-560">지속적인 관리와 위협 대응.</span><span class="sxs-lookup"><span data-stu-id="b54c0-560">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-561">다음 Microsoft Defender ATP 에이전트에 대한 온보딩 또는 구성:</span><span class="sxs-lookup"><span data-stu-id="b54c0-561">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="b54c0-562">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="b54c0-562">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-563">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="b54c0-563">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-564">Linux.</span><span class="sxs-lookup"><span data-stu-id="b54c0-564">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-565">모바일 장치(Android 및 iOS).</span><span class="sxs-lookup"><span data-stu-id="b54c0-565">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="b54c0-566">서버 온보딩 및 구성:</span><span class="sxs-lookup"><span data-stu-id="b54c0-566">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="b54c0-567">오프라인 통신을 위한 프록시 서버 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-567">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-568">하위 수준의 Configuration Manager 인스턴스 및 버전에서 Configuration Manager 배포 패키지 구성</span><span class="sxs-lookup"><span data-stu-id="b54c0-568">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-569">Azure Security Center에 서버 온보딩</span><span class="sxs-lookup"><span data-stu-id="b54c0-569">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-570">구성 관리자를 사용하여 관리하지 않는 서버.</span><span class="sxs-lookup"><span data-stu-id="b54c0-570">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="b54c0-571">macOS 온보딩 및 구성:</span><span class="sxs-lookup"><span data-stu-id="b54c0-571">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="b54c0-572">수동 Intune 기반 배포.</span><span class="sxs-lookup"><span data-stu-id="b54c0-572">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-573">JAMF 기반 배포.</span><span class="sxs-lookup"><span data-stu-id="b54c0-573">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="b54c0-574">기타 MDM(모바일 장치 관리) 제품 기반 배포.</span><span class="sxs-lookup"><span data-stu-id="b54c0-574">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-575">수동 배포.</span><span class="sxs-lookup"><span data-stu-id="b54c0-575">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="b54c0-576">다음 공격 표면 감소에 대한 기능:</span><span class="sxs-lookup"><span data-stu-id="b54c0-576">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="b54c0-577">하드웨어 기반 격리.</span><span class="sxs-lookup"><span data-stu-id="b54c0-577">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-578">앱 컨트롤</span><span class="sxs-lookup"><span data-stu-id="b54c0-578">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-579">악용 방지.</span><span class="sxs-lookup"><span data-stu-id="b54c0-579">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="b54c0-580">네트워크 방화벽.</span><span class="sxs-lookup"><span data-stu-id="b54c0-580">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="b54c0-581">Microsoft 위협 전문가 등록 또는 구성.</span><span class="sxs-lookup"><span data-stu-id="b54c0-581">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-582">API 또는 SIEM(보안 정보 및 이벤트 관리) 연결 검토 나는 구성 또는 교육</span><span class="sxs-lookup"><span data-stu-id="b54c0-582">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-583">MTP(Microsoft 위협 방지) 등록 또는 구성.</span><span class="sxs-lookup"><span data-stu-id="b54c0-583">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="b54c0-584">고급 헌팅에 대한 교육 또는 지침.</span><span class="sxs-lookup"><span data-stu-id="b54c0-584">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="b54c0-585">Kusto 쿼리의 사용 또는 만들기를 다루는 교육 또는 지침</span><span class="sxs-lookup"><span data-stu-id="b54c0-585">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="b54c0-586">이러한 서비스에 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">대한 지원을</a> 받기 만드리고 Microsoft 파트너에게 문의하세요.</span><span class="sxs-lookup"><span data-stu-id="b54c0-586">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>
