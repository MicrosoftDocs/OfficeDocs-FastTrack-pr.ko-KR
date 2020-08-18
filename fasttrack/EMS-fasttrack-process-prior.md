---
title: FastTrack 프로세스
description: FastTrack 센터 혜택 온보딩 프로세스 개요
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 7/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: de013ced738590e337080ed60221ea1205e4ae34
ms.sourcegitcommit: 81ad135578a329f8b0a3325c4e43bb8f90648597
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/17/2020
ms.locfileid: "46776996"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>EMS(Enterprise Mobility + Security)에 대한 FastTrack 센터 혜택 프로세스
조직이 EMS에 대한 FastTrack 센터 혜택을 받을 자격이 있는 경우 FastTrack 전문가와 원격으로 작업하여 Microsoft Azure Active Directory Premium, Microsoft Intune 및 Azure Information Protection을 사용할 준비를 할 수 있습니다. Azure Information Protection 및 Microsoft Cloud App Security에 대해 [FastTrack 사이트](https://www.microsoft.com/fasttrack/microsoft-365/ems)를 통해 도움을 요청할 수도 있습니다. 조직의 자격 여부를 알아보려면 [적합한 서비스 및 계획](M365-eligible-services-and-plans.md)을 참조하세요.


온보딩 프로세스에 대한 자세한 내용은 다음과 같습니다.

-   [온보딩 프로세스 개요](EMS-fasttrack-benefit-overview.md)

-   [필요한 원본 환경 요건](EMS-source-environment-expectations.md)

-   [온보딩 프로세스 단계](EMS-onboarding-phases.md)

-   각 단계에 대한 [FastTrack 책임](EMS-fasttrack-responsibilities.md)

-   각 단계에 대한 [고객 책임](EMS-your-responsibilities.md)

온보딩이 완료될 때 예상할 수 있는 결과는 다음과 같습니다.

-   선택한 서비스에 대한 EMS 테넌트가 생성됩니다.

-   라이선스가 있는 사용자는 다음 ID 옵션 중 하나를 사용하여 EMS 서비스에 액세스할 수 있습니다.

    -   클라우드 ID(고유한 EMS 계정)

    -   동기화된 ID: Azure Active Directory Connect 도구(암호 해시 동기화 또는 통과 인증)를 사용하여 온-프레미스 Active Directory에서 동기화된 EMS 계정입니다. 이 옵션은 단일 포리스트나 여러 Active Directory 포리스트가 있는 고객을 위한 것입니다.

    -   다음 Microsoft EMS 계정을 갖는 페더레이션 ID

        -   Azure AD Connect 도구를 사용하여 Active Directory와 동기화됩니다. 이 옵션은 단일 Active Directory 포리스트 구성을 사용하는 고객을 위한 것입니다.

        -   온-프레미스 Active Directory에서 Windows Server 2012 R2 AD FS(Active Directory Federation Services) 2.0 이상과 페더레이션되었습니다.

        -   Azure Information Protection을 사용하여 보관 중인 정보와 전송 중인 정보를 모두 자동으로 분류하고 보호할 수 있습니다. 

        -   Azure Information Protection 스캐너를 사용하여 온-프레미스 파일 공유와 SharePoint 서버 내에서 정보를 검색할 수 있습니다. 

        -   Azure Key Vault 내에서 Azure Information Protection 테넌트 키를 관리할 수 있습니다. 

