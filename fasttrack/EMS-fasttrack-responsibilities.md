---
title: FastTrack 책임
description: 고객이 EMS용 FastTrack 센터 혜택을 사용 중인 경우의 FastTrack 책임
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 6/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 62ed549ea78146541d0d4a2d860f02b15c02f44f
ms.sourcegitcommit: 826f140cc0ddee32005f74e5d995073af1dc3fa2
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/02/2020
ms.locfileid: "44471724"
---
# <a name="fasttrack-responsibilities"></a>FastTrack 책임

온보딩하는 동안 FastTrack은 다음을 수행합니다.

## <a name="general"></a>일반

-   자세한 단계 설명에 나와 있는 필수 구성 작업을 원격으로 지원합니다.

-   구성 작업을 줄이거나 없애는 데 도움이 되는 사용 가능한 설명서, 소프트웨어 도구 및 관리 콘솔을 제공합니다.

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

-   Intune 및 Azure AD Premium에 대한 재구성 검사 목록을 제공합니다.

## <a name="remediate-phase"></a>재구성 단계

-   합의된 일정에 따라 전화 회의를 실시하여 재구성 활동의 진행 상태를 검토합니다. 예를 들어 동의한 일정에 따라 사용자와 함께 전화 회의를 참석 하 여 업데이트 관리 활동의 진행 상황을 검토할 수 있습니다. 예를 들어 Microsoft 클라우드 서비스를 온보당하기 전에 설치 필수 구성 요소를 안내합니다.

## <a name="enable-phase"></a>사용 단계
다음에 대한 지침을 제공합니다.

-   Microsoft Online 서비스 테넌트 또는 구독을 활성화합니다.

-   TCP/IP 프로토콜 및 방화벽 포트 구성

-   적합한 서비스에 대한 DNS 구성

-   Microsoft Online 서비스에 대한 연결을 확인합니다.

-   단일 포리스트 환경:

    -   AD DS(Active Directory 도메인 서비스)와 적격한 Microsoft Online 서비스 간에 디렉터리 동기화 서버 설치(필요한 경우에만 지침 제공)

    -   Azure Active Directory Connect 도구를 사용하여 관리되는 인증(암호 해시 동기화 또는 통과 인증) 구성 (필요한 경우에만 지침 제공)

        > [!NOTE]
        > 사용자 지정 규칙 확장의 개발 및 구현은 다루지 않습니다.

-   페더레이션 ID가 대상인 경우 단일 포리스트: 필요한 경우 단일 사이트 내결함성 구성에서 Intune을 통해 로컬 도메인 인증을 받기 위한 AD FS(Active Directory Federation Services) 설치 및 구성

    > [!NOTE]
    > 모든 다중 포리스트 구성에 대한 ADFS 배포는 다루지 않습니다.

-   SSO(Single Sign-On) 기능을 배포한 경우 테스트

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>사용 단계 - Microsoft Azure Active Directory Premium

다음에 대한 지침을 제공합니다.

- Azure AD Premium 테넌트를 활성화

- 방화벽 포트 구성

- 적합한 서비스에 대한 DNS 구성

- Azure AD Premium 서비스에 대한 연결 확인

- 단일 포리스트 환경:

  -   필요한 경우 AD DS(Active Directory 도메인 서비스) 및 Azure AD Connect 간에 디렉터리 동기화 서버 설치

  -   Azure AD Connect 도구를 사용하여 인증 방법(암호 해시 동기화 또는 통과 인증) 구성

- 다중 포리스트 환경:

  -   Azure AD Connect 동기화를 설치하고 여러 포리스트 시나리오에 대해 설정합니다.
- 단일 및 다중 포리스트 환경:
  - 필요한 경우 Azure Active Directory 통과 인증을 구성합니다.
  - 필요한 경우 Azure Active Directory 원활한 SSO(Single Sign-On)를 구성합니다.
    > [!NOTE]
    > 사용자의 Active Directory 포리스트 간에 포리스트 트러스트가 있는 경우 및 이름 접미사 라우팅이 올바르게 구성된 경우 다중 포리스트 환경에 Azure Active Directory 통과 인증이 지원됩니다. 로그인 요청에 대한 고가용성을 제공하기 위해 여러 온-프레미스 서버에 추가 에이전트가 설치될 수 있습니다.

  - 자세한 내용은 [Azure Active Directory 통과 인증: 빠른 시작](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites) 및 [Azure Active Directory 원활한 Single Sign-On: 빠른 시작](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites)을 참조하세요.
  - 통과 인증 제한에 대한 자세한 내용은 [Azure Active Directory 통과 인증: 현재 제한](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations)을 참조하세요.
  - 원활한 SSO 문제에 대한 자세한 내용은 [Azure Active Directory 원활한 Single Sign-On 문제 해결](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso)을 참조하세요.

      > [!NOTE]
      > 암호 해시 동기화 및 암호 쓰기 저장은 여러 포리스트를 지원합니다. 하지만 다른 쓰기 저장 시나리오는 지원되지 않습니다.

  - 온-프레미스 Active Directory 포리스트 및 Microsoft Azure Active Directory Premium 디렉터리(Azure Active Directory) 간에 동기화를 구성합니다.

    > [!NOTE]
    > 사용자 지정 규칙 확장의 개발 및 구현은 다루지 않습니다.

- 페더레이션 ID가 대상인 경우 단일 포리스트:

  -   필요한 경우 단일 사이트 내결함성 구성에서 Azure AD Premium을 통해 로컬 도메인 인증을 받기 위한 AD FS 설치 및 구성

  > [!NOTE]
  > 모든 다중 포리스트 구성에 대한 ADFS 배포는 다루지 않습니다.

- 배포된 경우 SSO 기능 테스트

### <a name="enable-phase---azure-ad-premium---with-azure-ad-connect-and-ad-fs"></a>사용 단계 - Azure AD Premium - Azure AD Connect 및 AD FS 사용

설정에 대한 지침 제공:

- 라이선싱을 포함한 사용자 프로비저닝

- Azure AD Connect 디렉터리 동기화(암호 쓰기 저장 및 암호 해시 동기화 포함)

  - Azure Active Directory 셀프 서비스 암호 재설정(SSPR)

  - Azure Multi-factor Authentication

  - [Azure Active Directory 마켓플레이스](https://azure.microsoft.com/marketplace/active-directory/)에서 SSO(Single Sign-On)를 사용하여 최대 세 개 이상의 SaaS(Software as a Service) 응용 프로그램 통합

  - [앱 통합 자습서 목록](https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list)에 열거된 사전 통합된 SaaS 응용 프로그램에 대한 자동 사용자 프로비저닝(아웃바운드 프로비저닝으로만 제한됨)

  - 사용자 지정된 로그 화면(로고, 텍스트, 이미지 포함)

  - 셀프 서비스 및 동적 그룹(그룹)

  - Azure Active Directory 응용 프로그램 프록시

  - Azure Active Directory Connect 상태

  - Azure Active Directory 조건부 액세스

  - Azure Active Directory 사용 약관

  - Azure Active Directory ID 보호

  - Azure Active Directory Privileged Identity Management

  - Azure Active Directory 액세스 검토

  -   Azure Active Directory 암호 보호.

  -   Azure Active Directory B2B.

### <a name="enable-phase---intune"></a>사용 단계 - Intune

> [!IMPORTANT]
> FastTrack은 Intune을 통한 Windows 10 클래식 PC 관리를 지원하지 않습니다. FastTrack은 Intune MDM(모바일 장치 관리)를 통한 Windows 10 관리만 지원합니다.

다음에 대한 지침을 제공합니다.

-   온-프레미스 Active Directory 또는 클라우드 ID(Azure Active Directory)를 활용하여 Intune에서 사용할 ID 구성

-   최종 사용자에게 라이선스 부여

-   Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 장치 그룹 만들기

-   다음을 비롯한 관리 요구 사항에 따라 MDM(모바일 장치 관리) 기관 구성

    -   Intune을 MDM 기관으로 설정

    -   MDM 관리 정책의 유효성을 검사하는 데 사용할 테스트 그룹 구성

    -   Intune 관리 포털을 탐색하여 사용자 및 장치에 대한 정보 찾기

    -   Intune 역할 설정(지원 센터 운영자, 관리자 등)

    -   다음과 같은 MDM 관리 정책 및 서비스 구성

        -   웹 링크, MSI 및/또는 딥 링크를 통해 지원되는 각 플랫폼용 앱 배포

        -   Windows 10 장치에 Office ProPlus 배포

        -   Apple의 VPP, 비즈니스용 Windows 스토어, Google의 Play for Work Store를 비롯한 앱 배포에 대한 볼륨 구매 프로그램

        -   조직에서 기존 인증 기관, Wi-fi 또는 VPN 인프라를 보유하고 있는 경우 전자 메일, 무선 네트워크, VPN 프로필 배포

        -   Microsoft Intune Exchange Connector 설정(해당하는 경우)

        -   지원되는 장치 플랫폼에 대한 장치 구성 프로필

    -   조건부 액세스 정책 설정

    -   지원되는 각 플랫폼에 대한 Intune 앱 보호 정책 구성 및 배포

    -   Intune 앱 보호 정책을 위한 LOB(기간 업무) 앱 준비(사용 가능한 옵션 관련 지침 포함)

    -   Microsoft Intune 서비스를 사용하여 Intune 또는 Configuration Manager에 지원되는 각 플랫폼 장치 등록

    -   Intune 데이터 웨어하우스에 연결

    -   다음에 Intune 통합:
        -   원격 지원을 위한 팀 뷰어(팀 뷰어 구독 필수)

        -   Mobile Threat Defense 파트너 솔루션(Mobile Threat Defense 파트너 솔루션 구독 필수)

        -   Telecom Expense Management 솔루션(Telecom Expense Management 구독 필수)

        -   Microsoft Defender Advanced Threat Protection(Windows E5 또는 Microsoft 365 E5 라이선스가 필요합니다).

    -   지원되는 해당 플랫폼에 맞게 소프트웨어 업데이트 구성

    -   사용자 채택 계획에 대한 리소스

- Windows Autopilot 설정:

    - Windows Autopilot용 Microsoft Intune을 구성하고 설정합니다.

    - Azure AD 동적 그룹 구성

    - Azure AD에 회사 브랜드를 추가합니다.

    - 장치를 만든 후 Windows Autopilot 프로필(예: 로컬 관리자 계정 만들기를 제한하는 Windows Autopilot 프로필)에 할당합니다.

    - 조직의 요구 사항을 준수하도록 OOBE(Out-of-Box-Experience)를 사용자 지정합니다.

    - Azure AD 및 Intune에서 MDM 자동 등록 구성

    > [!NOTE]
    > Intune 외부에서 Windows Autopilot 설정은 FastTrack 혜택의 범위를 벗어납니다.

### <a name="enable-phase---cloud-attach"></a>활성화 단계 - 클라우드 연결

다음에 대한 지침을 제공합니다.

-   최종 사용자에게 라이선스 부여

-   Configuration Manager 콘솔에서 클라우드 연결을 구현합니다.

-   Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기(Intune을 설치하지 않은 경우)

-   하이브리드 Azure Active Directory 참가를 설정합니다.

-   MDM 자동 등록을 위해 Azure Active Directory 설정

-   클라우드 관리 게이트웨이를 설정합니다.

-   Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기

-   디바이스 관리를 위해 Intune 서비스 준비.

-   MDM(모바일 디바이스 관리) 기관을 Intune으로 설정합니다.

-   MDM 관리 정책의 유효성을 검사하는 데 사용할 테스트 그룹 구성

-   Intune 관리 포털을 탐색하여 사용자 및 장치에 대한 정보 찾기

-   Intune 역할 설정(헬프데스크 운영자, 관리자 등)

-   Intune에 Windows 10 디바이스 등록

-   원하는 대로 Intune에서 관리 작업을 전환합니다.

### <a name="enable-phase--azure-information-protection"></a>사용 단계 - Azure Information Protection

다음에 대한 지침을 제공합니다. 

- 고객 테넌트 활성화 및 구성

- 레이블과 정책 만들기 및 설정

- 문서에 정보 보호 적용 

- Azure Information Protection 클라이언트를 사용하여 Windows에서 실행 중인 Office 앱(Word, PowerPoint, Excel, Outlook 등)에서 자동으로 정보 분류 및 레이블 지정

- Azure Information Protection 스캐너를 통해 보관 중인 파일 사용

- Exchange Online 메일 흐름 규칙을 사용하여 전송 중인 전자 메일 모니터링

Microsoft Azure RMS(권한 관리 서비스), OME(Office 365 메시지 암호화) 및 DLP(데이터 손실 방지)를 사용하여 보호를 적용하려는 고객에게도 지침이 제공됩니다.

> [!NOTE]
> **추가 정보가 필요하십니까?** [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)를 참조하세요.

## <a name="next-steps"></a>다음 단계

[EMS용 FastTrack 혜택 - 책임](EMS-your-responsibilities.md)

