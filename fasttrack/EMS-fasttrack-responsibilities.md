---
title: FastTrack 책임
description: 고객이 EMS에 대 한 fasttrack 센터 혜택을 사용 하는 경우 fasttrack의 책임
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 03/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 25602322bc92823cd50f4674a683762d9eeae10b
ms.sourcegitcommit: 5abb49be2bfa99110f17245839c3468318b8a3db
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/01/2019
ms.locfileid: "30359962"
---
# <a name="fasttrack-responsibilities"></a>FastTrack 책임

fasttrack 온 보 딩 중에는 다음과 같은 책임이 있습니다.

## <a name="general"></a>일반

-   자세한 단계 설명에 나와 있는 것 처럼 필요한 구성 작업에 대 한 원격 지원 지원을 제공 합니다.

-   구성 작업을 줄이거나 없애는 데 도움이 되는 사용 가능한 설명서, 소프트웨어 도구 및 관리 콘솔을 제공 합니다.

## <a name="initiate-phase"></a>시작 단계

-   온보딩을 시작하도록 지원합니다.

-   온보딩할 적합한 서비스를 정의합니다.

## <a name="assess-phase"></a>평가 단계

-   관리 개요를 제공합니다.

-   다음에 대한 지침을 제공합니다.

    -   DNS, 네트워크 및 인프라 요구

    -   클라이언트 요구(인터넷 브라우저, 클라이언트 운영 체제 및 서비스 요구)

    -   사용자 ID 및 프로비전

    -   구매한 후 온보딩의 일부로 정의한 해당 서비스 사용

-   재구성 작업을 위한 일정을 지정합니다.

-   Intune 및 Azure AD Premium에 대 한 재구성 검사 목록을 제공 합니다.

## <a name="remediate-phase"></a>재구성 단계

-   합의 된 일정에 따라 전화 회의를 실시 하 여 재구성 작업의 진행 상황을 검토 하 고, 예를 들어 Microsoft 클라우드 서비스에 대 한 설치 전 필수 구성 요소를 안내 합니다.

## <a name="enable-phase"></a>사용 단계
다음에 대한 지침을 제공합니다.

-   Microsoft online 서비스 테 넌 트 또는 구독을 활성화 합니다.

-   TCP/IP 프로토콜 및 방화벽 포트 구성

-   적합한 서비스에 대한 DNS 구성

-   Microsoft online services에 대 한 연결 유효성 검사

-   단일 포리스트 환경:

    -   AD DS (Active directory 도메인 서비스)와 적격 Microsoft online 서비스 간에 디렉터리 동기화 서버 설치 (필요한 경우에만 해당)

    -   Azure Active Directory Connect 도구를 사용 하 여 관리 되는 인증 (암호 해시 동기화 또는 통과 인증)을 구성 합니다. (필요한 경우에만 지침을 제공 합니다.)

        > [!NOTE]
        > 사용자 지정 규칙 확장에 대 한 개발 및 구현이 범위를 벗어났습니다.

-   대상이 페더레이션 id 인 경우 단일 포리스트: 필요한 경우 단일 사이트 내결함성 구성에서 Intune을 사용 하 여 로컬 도메인 인증을 위한 AD FS (Active Directory Federation Services) 설치 및 구성

    > [!NOTE]
    > 모든 다중 포리스트 구성에서 adfs 배포는 범위를 벗어납니다.

-   sso (single sign-on) 기능을 테스트 했습니다 (배포 된 경우).

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>사용 단계-Microsoft Azure Active Directory Premium

다음에 대한 지침을 제공합니다.

- Azure AD Premium 테 넌 트 활성화

- 방화벽 포트 구성

- 적합한 서비스에 대한 DNS 구성

- Azure AD Premium 서비스에 대 한 연결 유효성 검사

- 단일 포리스트 환경:

  -   필요한 경우 ad DS (Active directory 도메인 서비스) 및 Azure ad Connect 간에 디렉터리 동기화를 설치 합니다.

  -   Azure AD Connect 도구를 사용 하 여 인증 방법 (암호 해시 동기화 또는 통과 인증) 구성

- 다중 포리스트 환경의 경우:

  -   Azure AD Connect 동기화 설치, 여러 포리스트 시나리오에 대해 설정
- 단일 및 다중 포리스트 환경:
  - 필요한 경우 Azure Active Directory 통과 인증을 구성합니다.
  - 필요한 경우 Azure Active Directory 원활한 SSO(Single Sign-On)를 구성합니다.
    > [!NOTE]
    > active directory 포리스트 간에 포리스트 트러스트가 있고 이름 접미사 라우팅이 올바르게 구성 된 경우 다중 포리스트 환경에 대 한 Azure Active Directory 통과 인증이 지원 됩니다. 로그인 요청에 대 한 고가용성을 제공 하기 위해 여러 온-프레미스 서버에 추가 에이전트를 설치할 수 있습니다.

  - 자세한 내용은 [Azure Active Directory 통과 인증: 빠른 시작](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites) 및 [Azure Active Directory 원활한 Single Sign-On: 빠른 시작](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites)을 참조하세요.
  - 통과 인증 제한에 대한 자세한 내용은 [Azure Active Directory 통과 인증: 현재 제한 사항](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations)을 참조하세요.
  - 원활한 SSO 문제에 대한 자세한 내용은 [Azure Active Directory 원활한 Single Sign-On 문제 해결](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso)을 참조하세요.

      > [!NOTE]
      > 암호 해시 동기화 및 암호 쓰기 저장은 여러 포리스트를 지원 합니다. 그러나 다른 쓰기 저장 시나리오는 지원 되지 않습니다.

  - 온-프레미스 Active directory 포리스트와 Microsoft azure active directory Premium 디렉터리 (Azure active directory) 간의 동기화를 구성 합니다.

    > [!NOTE]
    > 사용자 지정 규칙 확장에 대 한 개발 및 구현이 범위를 벗어났습니다.

- 대상이 페더레이션 id 인 경우 단일 포리스트:

  -   단일 사이트 내결함성 구성 (필요한 경우)에서 Azure AD Premium을 사용 하 여 로컬 도메인 인증용 AD FS 설치 및 구성

  > [!NOTE]
  > 모든 다중 포리스트 구성에서 adfs 배포는 범위를 벗어납니다.

- SSO 기능 테스트 (배포 된 경우)

### <a name="enable-phase---azure-ad-premium--with-azure-ad-connect-and-ad-fs"></a>Enable phase-azure ad Connect 및 ad FS 사용

설정에 대 한 지침을 제공 합니다.

- 라이선스를 비롯 한 사용자 프로 비전

- Azure AD Connect 디렉터리 동기화 (암호 쓰기 저장 및 암호 해시 동기화 사용)

  - Azure Active Directory 셀프 서비스 암호 재설정 (SSPR)

  - Azure multi-factor Authentication

  - [Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/)에서 sso (Single sign-on)를 사용한 SaaS (Software as a Service) 응용 프로그램 통합 (3 개 이상)

  - [앱 통합 자습서 목록](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/tutorial-list)에 나열 된 미리 통합 된 SaaS 응용 프로그램에 대 한 자동 사용자 프로 비전으로, 아웃 바운드 프로 비전 으로만 제한 됩니다.

  - 로고, 텍스트 및 이미지를 포함 하는 사용자 지정 된 로그온 화면

  - 셀프 서비스 및 동적 그룹 (그룹)

  - Azure Active Directory 응용 프로그램 프록시

  - Azure Active Directory Connect Health입니다.

  - Azure Active Directory 조건부 액세스

  - Azure Active Directory 사용 약관

  - Azure Active Directory id 보호

  - Azure Active Directory 권한 있는 id 관리

  - Azure Active Directory 액세스 검토

### <a name="enable-phase---intune"></a>사용 단계-Intune

> [!IMPORTANT]
> fasttrack은 Intune을 사용 하 여 Windows 10 클래식 PC 관리를 지원 하지 않습니다. fasttrack은 Intune MDM (모바일 장치 관리)을 통해서만 Windows 10 관리를 지원 합니다.

다음에 대 한 **지침** 을 제공 합니다.

-   온-프레미스 Active directory 또는 클라우드 id (Azure Active directory)를 활용 하 여 Intune에서 사용할 id를 구성 합니다.

-   최종 사용자에 게 라이선스를 부여 합니다.

-   Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 장치 그룹 만들기

-   다음을 포함 하 여 관리 요구 사항에 따라 모바일 장치 관리 MDM 사용 권한 구성

    -   Intune을 MDM 기관으로 설정 합니다.

    -   MDM 관리 정책의 유효성을 검사 하는 데 사용할 테스트 그룹 구성

    -   Intune 관리 포털을 탐색 하 여 사용자 및 장치에 대 한 정보를 찾습니다.

    -   Intune 역할 (지원 센터 운영자, 관리자 등) 설정

    -   다음과 같은 MDM 관리 정책 및 서비스 구성

        -   웹 링크, MSI 및/또는 딥 링크를 통해 지원 되는 각 플랫폼용 앱 배포

        -   Windows 10 장치에 Office ProPlus 배포

        -   Apple의 VPP, 비즈니스용 Windows 스토어 및 Google 's 직장 스토어 플레이를 비롯 한 앱 배포를 위한 대량 구매 프로그램

        -   조직의 기존 인증 기관, wi-fi 또는 vpn 인프라를 사용 하는 경우 전자 메일, 무선 네트워크 및 vpn 프로필 배포

        -   Microsoft Intune Exchange Connector를 설정 하는 경우 (해당 하는 경우)

        -   지원 되는 장치 플랫폼에 대 한 장치 구성 프로필입니다.

    -   조건부 액세스 정책 설정

    -   지원 되는 각 플랫폼에 대해 Intune 앱 보호 정책 구성 및 배포

    -   사용 가능한 옵션에 대 한 지침을 포함 하 여 Intune 앱 보호 정책에 대 한 lob (기간 업무) 앱을 준비 합니다.

    -   지원 되는 각 플랫폼의 장치를 intune 또는 Microsoft intune 서비스를 사용 하는 Configuration Manager에 등록

    -   Intune 데이터 웨어하우스에 연결 합니다.

    -   Intune을 다음에 통합:
        -   team viewer for remote 지원 (team viewer 구독이 필요 함)

        -   모바일 위협 방어 파트너 솔루션 (모바일 위협 방어 파트너 솔루션 구독이 필요 함).

        -   텔레콤 경비 관리 솔루션 (통신 경비 관리 솔루션 구독이 필요 함).

        -   windows Defender Advanced Threat Protection (windows E5 또는 Microsoft 365 E5 라이선스가 필요 함).

    -   해당 하는 지원 되는 플랫폼에 대 한 소프트웨어 업데이트 구성

    -   사용자 채택 계획 용 리소스

- Windows Autopilot 설정:

    - Windows Autopilot 용 Microsoft Intune을 구성 하 고 설치 합니다.

    - Azure AD 동적 그룹 구성

    - Azure AD에 회사 브랜딩을 추가 합니다.

    - windows Autopilot 프로필 (예: 로컬 관리자 계정 만들기를 제한 하는 windows Autopilot 프로필)에 디바이스를 만들고 할당 합니다.

    - OOBE (기본 사용 환경)를 사용자 지정 하 여 조직의 요구 사항을 준수 합니다.

    - Azure AD 및 Intune에서 MDM 자동 등록을 구성 합니다.

    > [!NOTE]
    > Windows Autopilot 외부 Intune을 설정 하는 것은 fasttrack 혜택 범위를 벗어납니다.

### <a name="enable-phase---co-management"></a>사용 단계 공동 관리

다음에 대한 지침을 제공합니다.

-   최종 사용자에 게 라이선스를 부여 합니다.

-   intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 장치 그룹 만들기 (Intune이 설치 되지 않은 경우)

-   MDM 자동 등록에 대 한 Azure Active Directory를 설정 합니다.

-   하이브리드 Azure Active Directory Join을 설정 합니다.

-   클라우드 관리 게이트웨이를 설정 합니다.

-   Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 장치 그룹 만들기

-   intune (intune이 설치 되지 않은 경우)을 준비 합니다.

    -   다음을 포함 하 여 관리 요구 사항에 따라 모바일 장치 관리 MDM 사용 권한 구성

    -   Intune을 MDM 기관으로 설정 합니다.

    -   MDM 관리 정책의 유효성을 검사 하는 데 사용할 테스트 그룹 구성

    -   Intune 관리 포털을 탐색 하 여 사용자 및 장치에 대 한 정보를 찾습니다.

    -   Intune 역할 (지원 센터 운영자, 관리자 등) 설정

    -   지원 되는 각 플랫폼에 대해 Intune 앱 보호 정책 구성 및 배포

    -   Intune에 Windows 10 장치 등록

- Configuration Manager 콘솔에서 공동 관리를 사용 하도록 설정 합니다.

- 작업을 Intune으로 전환 합니다.

- 해당 환경의 공동 관리 작업을 모니터링 합니다.

> [!NOTE]
> **자세한 정보를 원하십니까?** [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)를 참조 하세요.

## <a name="next-steps"></a>다음 단계

[EMS에 대 한 fasttrack 혜택](EMS-your-responsibilities.md)
