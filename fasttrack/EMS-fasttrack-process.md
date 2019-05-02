---
title: FastTrack 프로세스
description: FastTrack 센터 혜택 온 보 딩 프로세스 개요
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 1e3f34284cb4b6300a50116ad2bb1df3cb6ab0fe
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513777"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>EMS(Enterprise Mobility + Security)에 대한 FastTrack 센터 혜택 프로세스
조직이 EMS에 대 한 FastTrack 센터 혜택을 받을 자격이 있는 경우 FastTrack 전문가와 원격으로 작업 하 여 Microsoft Azure Active Directory Premium, Microsoft Intune 및 Azure Information Protection을 사용할 수 있도록 준비 해야 합니다. 또한 Azure Information Protection, Microsoft Cloud App Security 및 Microsoft Advanced Threat Analytics에 대 한 [Fasttrack 사이트](https://www.microsoft.com/fasttrack/microsoft-365/ems) 를 통해 도움을 요청할 수 있습니다. 조직이 적합 한지 여부를 확인 하려면 적합 한 [서비스 및 요금제](M365-eligible-services-and-plans.md)를 참조 하세요.


다음은 온 보 딩 프로세스에 대 한 설명입니다.

-   [온 보 딩 프로세스 개요](EMS-fasttrack-benefit-overview.md)

-   [원본 환경에 대 한 기대치](EMS-source-environment-expectations.md)

-   [온 보 딩 프로세스의 단계](EMS-onboarding-phases.md)

-   각 단계에 대 한 [Fasttrack 책임](EMS-fasttrack-responsibilities.md)

-   각 단계에 대 한 [고객의 책임](EMS-your-responsibilities.md)

온 보 딩이 완료 되 면 예상 되는 결과는 다음과 같습니다.

-   선택한 서비스에 대 한 EMS 테 넌 트가 만들어집니다.

-   라이선스가 있는 사용자는 다음 id 옵션 중 하나를 사용 하 여 EMS 서비스에 액세스할 수 있습니다.

    -   클라우드 Id (고유한 EMS 계정)

    -   동기화 된 Id: Azure Active Directory 연결 도구 (암호 해시 동기화 또는 통과 인증)를 사용 하 여 온-프레미스 Active Directory에서 동기화 되는 EMS 계정입니다. 이 옵션은 단일 포리스트나 여러 Active Directory 포리스트가 있는 고객에 게 적합 합니다.

    -   페더레이션 Id--다음에 해당 하는 Microsoft EMS 계정을 포함 합니다.

        -   Azure AD Connect 도구를 사용 하 여 Active Directory에서 동기화 됨 이 옵션은 단일 Active Directory 포리스트 구성을 사용 하는 고객에 게 적합 합니다.

        -   온-프레미스 Active Directory에서 Windows Server 2012 R2 AD FS (Active Directory Federation Services) 2.0 이상에 연결 되었습니다.

        -   Rest 및 Azure Information Protection을 통한 전송에서 정보를 자동으로 분류 하 고 보호 하는 기능입니다. 

        -   Azure Information Protection 검색 프로그램을 사용 하 여 온-프레미스 파일 공유 및 SharePoint 서버 내에서 정보를 검색할 수 있는 기능 

        -   Azure 키 자격 증명 모음 내에서 Azure Information Protection 테 넌 트 키를 관리 하는 기능입니다. 
