---
title: fasttrack 프로세스
description: fasttrack 센터 혜택 온 보 딩 프로세스 개요
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 03/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 0516035e55bc791645b32ad1819839b6c73f1772
ms.sourcegitcommit: 5abb49be2bfa99110f17245839c3468318b8a3db
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/01/2019
ms.locfileid: "30359842"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a><span data-ttu-id="a75b6-103">EMS(Enterprise Mobility + Security)에 대한 FastTrack 센터 혜택 프로세스</span><span class="sxs-lookup"><span data-stu-id="a75b6-103">FastTrack Center Benefit Process for Enterprise Mobility + Security (EMS)</span></span>
<span data-ttu-id="a75b6-p101">조직이 EMS에 대 한 fasttrack 센터 혜택을 받을 자격이 있는 경우 fasttrack 전문가와 원격으로 작업 하 여 microsoft Azure Active Directory Premium 및 microsoft Intune을 사용할 수 있도록 준비 해야 합니다. 또한 Azure Information Protection, microsoft Cloud App Security 및 microsoft Advanced Threat Analytics에 대 한 [fasttrack 사이트](https://www.microsoft.com/fasttrack/microsoft-365/ems) 를 통해 도움을 요청할 수 있습니다. 조직이 적합 한지 여부를 확인 하려면 적합 한 [서비스 및 요금제](M365-eligible-services-and-plans.md)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="a75b6-p101">If your organization is eligible for the FastTrack Center Benefit for EMS, you can work remotely with FastTrack Specialists to get Microsoft Azure Active Directory Premium and Microsoft Intune ready for use. You can also request help through the [FastTrack site](https://www.microsoft.com/fasttrack/microsoft-365/ems) for Azure Information Protection, Microsoft Cloud App Security and Microsoft Advanced Threat Analytics. To learn whether your organization is eligible, see [Eligible Services and Plans](M365-eligible-services-and-plans.md).</span></span>


<span data-ttu-id="a75b6-107">다음은 온 보 딩 프로세스에 대 한 설명입니다.</span><span class="sxs-lookup"><span data-stu-id="a75b6-107">Here's what we cover about the onboarding process:</span></span>

-   [<span data-ttu-id="a75b6-108">온 보 딩 프로세스 개요</span><span class="sxs-lookup"><span data-stu-id="a75b6-108">Overview of the onboarding process</span></span>](EMS-fasttrack-benefit-overview.md)

-   [<span data-ttu-id="a75b6-109">필요한 원본 환경 요건</span><span class="sxs-lookup"><span data-stu-id="a75b6-109">Expectations for your source environment</span></span>](EMS-source-environment-expectations.md)

-   [<span data-ttu-id="a75b6-110">온 보 딩 프로세스의 단계</span><span class="sxs-lookup"><span data-stu-id="a75b6-110">Phases of the onboarding process</span></span>](EMS-onboarding-phases.md)

-   <span data-ttu-id="a75b6-111">각 단계에 대 한 [fasttrack 책임](EMS-fasttrack-responsibilities.md)</span><span class="sxs-lookup"><span data-stu-id="a75b6-111">[FastTrack responsibilities](EMS-fasttrack-responsibilities.md) for each phase</span></span>

-   <span data-ttu-id="a75b6-112">각 단계에 대 한 [고객의 책임](EMS-your-responsibilities.md)</span><span class="sxs-lookup"><span data-stu-id="a75b6-112">[Customer responsibilities](EMS-your-responsibilities.md) for each phase</span></span>

<span data-ttu-id="a75b6-113">온보딩이 완료될 때 예상할 수 있는 결과는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="a75b6-113">Here’s what you can expect when onboarding is complete:</span></span>

-   <span data-ttu-id="a75b6-114">선택한 서비스에 대 한 EMS 테 넌 트가 만들어집니다.</span><span class="sxs-lookup"><span data-stu-id="a75b6-114">Your EMS tenants for your selected services are created.</span></span>

-   <span data-ttu-id="a75b6-115">라이선스가 있는 사용자는 다음 id 옵션 중 하나를 사용 하 여 EMS 서비스에 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a75b6-115">Licensed users can access EMS Services by using one of the following identity options:</span></span>

    -   <span data-ttu-id="a75b6-116">클라우드 id (고유한 EMS 계정)</span><span class="sxs-lookup"><span data-stu-id="a75b6-116">Cloud Identities (unique EMS accounts).</span></span>

    -   <span data-ttu-id="a75b6-p102">동기화 된 id: Azure Active directory 연결 도구 (암호 해시 동기화 또는 통과 인증)를 사용 하 여 온-프레미스 Active directory에서 동기화 되는 EMS 계정입니다. 이 옵션은 단일 포리스트나 여러 Active Directory 포리스트가 있는 고객에 게 적합 합니다.</span><span class="sxs-lookup"><span data-stu-id="a75b6-p102">Synchronized Identities: EMS accounts synchronized from your on-premises Active Directory by using the Azure Active Directory Connect tool (Password Hash Sync or Pass-through Authentication). This option is for customers with a single forest or multiple Active Directory forests.</span></span>

    -   <span data-ttu-id="a75b6-119">페더레이션 id--다음에 해당 하는 Microsoft EMS 계정을 포함 합니다.</span><span class="sxs-lookup"><span data-stu-id="a75b6-119">Federated Identities--with Microsoft EMS accounts that are:</span></span>

        -   <span data-ttu-id="a75b6-p103">Azure AD Connect 도구를 사용 하 여 Active Directory에서 동기화 됨 이 옵션은 단일 Active Directory 포리스트 구성을 사용 하는 고객에 게 적합 합니다.</span><span class="sxs-lookup"><span data-stu-id="a75b6-p103">Synchronized from Active Directory with the Azure AD Connect tool. This option is for customers with a single Active Directory forest configuration.</span></span>

        -   <span data-ttu-id="a75b6-122">온-프레미스 Active directory에서 Windows Server 2012 R2 AD FS (Active Directory Federation Services) 2.0 이상에 연결 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="a75b6-122">Federated with Windows Server 2012 R2 Active Directory Federation Services (AD FS) 2.0 or later from your on-premises Active Directory.</span></span>
