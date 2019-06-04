---
title: 부록 B FastTrack 센터의 추가 장점
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 06/04/2019
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Priority
description: Exchange Online 테넌트용 라이선스를 20,000개 이상 구입한 고객은 FastTrack 센터 추가 서비스를 받을 자격이 있습니다. 자세한 내용은 적합한 서비스 및 계획을 참조하세요.
ms.openlocfilehash: 44cbba5e3ec5e1011c9673611a0143a7b1ba13ec
ms.sourcegitcommit: 0e76ab0f36619dee923201098936573be14b4560
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/03/2019
ms.locfileid: "34673417"
---
# <a name="appendix-b---fasttrack-center-additional-benefit"></a>부록 B - FastTrack 센터의 추가 혜택

Exchange Online 테넌트용 라이선스를 20,000개 이상 구입한 고객은 FastTrack 센터 추가 서비스를 받을 자격이 있습니다. 자세한 내용은 [적합한 서비스 및 계획](M365-eligible-services-and-plans.md)을 참조하세요. 
  
## <a name="onboarding-and-migration-phases"></a>온보딩 및 마이그레이션 단계

## <a name="core"></a>핵심

핵심 온보딩 서비스 추가 기능에는 서비스에 대한 지역 중복 AD FS(Active Directory Federation Services) 및 AD FS 클라이언트 액세스 정책에 대한 구성 지침이 포함되어 있습니다. 
  
## <a name="exchange-online"></a>Exchange Online

Exchange Online의 경우 다음에 대한 구성 지침을 제공합니다.
- Exchange Online에서 UM(통합 메시징) 설정
- Exchange Online 및 기존 온-프레미스 공용 폴더 간 공존 구성
- 메일 사용이 가능한 응용 프로그램 통합 
- 사서함 마이그레이션 계획 및 그룹화
    
## <a name="skype-for-business-online"></a>비즈니스용 Skype Online

비즈니스용 Skype 온라인의 경우 비즈니스용 Skype 온라인으로의 온-프레미스 Lync 및 비즈니스용 Skype 사용자 마이그레이션에 대한 지침을 제공합니다.
  
## <a name="office-365-proplus"></a>Office 365 ProPlus

Office 365 ProPlus의 경우 다음에 대한 지침을 제공합니다. 
- 평가 및 계획은 Microsoft의 모범 사례와 일치하는 업데이트의 초기 배포 및 관리를 위한 환경 준비에 중점을 둡니다. 
- Office 365 배포 도구를 사용해서 배포 구성과 업데이트 설정을 개발합니다. 
- System Center Configuration Manager를 사용하는 개발 패키징  
- Office 원격 분석을 배포 및 구성하여 응용 프로그램 호환성을 위해 업무에 중요한 Office 문서 및 솔루션의 사용을 평가할 수 있는 지침을 제공합니다.
    
## <a name="fasttrack-responsibilities"></a>FastTrack 책임

온보딩하는 동안 FastTrack Specialist는 다음을 수행합니다. 이러한 작업은 [FastTrack 책임](O365-fasttrack-responsibilities.md)에 정의된 활동 외에 추가로 또는 이러한 활동 대신 수행될 수 있습니다.
  
## <a name="general"></a>일반

- 사용자의 성공적인 계획 개발 및 구현과 [온보딩 및 마이그레이션 단계](#onboarding-and-migration-phases)에 나와 있는 필수 구성 작업을 원격으로 지원합니다.
    
## <a name="assess-phase"></a>평가 단계

- 성공적인 계획 통화를 실시하여 성공적인 사용자 채택을 위한 지침을 제공합니다. 
- 지역 중복 AD FS 구성을 지원하도록 환경을 평가합니다.  
- AD FS 클라이언트 액세스에 대한 요구 사항을 식별하는 평가를 실행합니다.
    
## <a name="enable-phase"></a>사용 단계

### <a name="geo-redundant-ad-fs-guidance"></a>지역 중복 AD FS 지침

- 2개의 데이터 센터에 걸쳐 있는 지역 중복 ADFS 토폴로지에 대한 표준 참조 아키텍처 설계를 제공합니다. 다음에 대한 표준 아키텍처를 제공합니다.
  - 범위 내 서비스에서 FastTrack 센터 혜택에 대한 페더레이션 인증 
  - 단일 사이트 복구  
  - 고가용성 및 장애 조치(failover)  
  - 크기 조정 지침 
- Windows 내부 데이터베이스 및 SQL Server를 AD FS 팜에 대한 데이터베이스 인스턴스로 사용하기 위한 지침을 제공합니다.   
- 범위 내의 각 포리스트에 대해 설정된 페더레이션된 인증의 유효성을 검사합니다.  
- 최대 10명의 사용자에 대한 페더레이션된 인증 기능을 확인합니다.
    
> [!NOTE]
> AD FS 배포는 다중 Active Directory 포리스트 구성을 가지며 추가 기능을 사용할 수 있는 자격이 있는 고객을 대상으로 합니다. 
  
### <a name="ad-fs-client-access-policy-guidance"></a>AD FS 클라이언트 액세스 정책 지침

- Office 365 리소스의 보안을 유지하는 데 필요한 정책 및 구성을 검토합니다.  
- 지원되는 시나리오의 범위 내에서 확인된 클라이언트 액세스 시나리오에 대해 AD FS 클라이언트 액세스 정책을 구성하기 위한 지침 및 지원을 제공합니다. 자세한 내용은 [클라이언트 위치를 기준으로 Office 365 서비스에 대한 액세스 제한](https://go.microsoft.com/fwlink/?LinkID=525689)을 참조하세요. 
- 최대 10명의 사용자가 포함된 구성의 식별된 액세스 시나리오에 대해 수정된 클라이언트 액세스 정책을 사용하여 페더레이션된 인증 기능이 유효한지 확인합니다.
    
## <a name="exchange-online"></a>Exchange Online

### <a name="exchange-unified-messaging-guidance"></a>Exchange 통합 메시징 지침

- 다음을 10개까지 허용하는 Exchange Online의 필수 구성에 대한 지침을 제공합니다. 
  - UM 다이얼 플랜   
  - UM 사서함 정책 
  - 자동 전화 교환  
- UM을 사용하도록 설정하고 구체적으로 대상을 지정하기 위한 온-프레미스 Lync 또는 비즈니스용 Skype 환경 구성에 대한 지침을 제공합니다.  
  - Exchange Online 호스트된 정책  
  - Exchange Online 호스트된 음성 메일 정책 
  - 사용자를 Exchange Online으로 리디렉션하기 위한 UM 자동 전화 교환 연락처 및 Outlook 음성 메일 
  - 페더레이션에 필요한 경우 서비스 위치(SRV) 레코드의 생성을 지원합니다.
> [!NOTE]
> UM은 지원되는 UM IP 게이트웨이 및 SBC(Session Border Controller)로 구성될 수 있습니다. 자세한 내용은 [UM과의 전화 시스템 통합](https://go.microsoft.com/fwlink/?LinkID=809293)을 참조하세요. 
  
### <a name="public-folder-coexistence-guidance"></a>공용 폴더 공존 지침

- 다음을 포함하는 단일 공용 폴더 트리 공존에 대한 지침을 제공합니다.  
  - Exchange 2007, Exchange 2010 및 Exchange 2013의 공용 폴더 준비 
  - Exchange 2007, Exchange 2010 및 Exchange 2013 공용 폴더 계층 구조와 Exchange Online의 동기화에 필요한 Windows PowerShell cmdlet  
  - 공용 폴더 액세스를 온-프레미스 공용 폴더로 리디렉션하기 위한 Exchange Online 구성  
  - Exchange Online에서 단일 Exchange 2007, Exchange 2010 또는 Exchange 2013 온-프레미스 환경으로의 공용 폴더 액세스 구성  
  - Exchange Online에서 최대 10명 사용자의 공용 폴더 환경에 대한 액세스 유효성 검사 지원
    
### <a name="mail-enabled-application-integration-guidance"></a>메일 사용이 가능한 응용 프로그램 통합 지침

- 다음에 대한 지침 템플릿을 제공합니다.  
  - 대량 메일 응용 프로그램  
  - Exchange를 통해 전자 메일을 보내는 응용 프로그램  
  - Exchange 사서함을 사용하는 응용 프로그램  
  - 타사 또는 사용자 지정 구성 요소를 Exchange 서버에 설치해야 하는 응용 프로그램
    
### <a name="mailbox-migration-planning-and-grouping"></a>사서함 마이그레이션 계획 및 그룹화

- 다음을 포함하여 마이그레이션 계획 생성에 대한 지침을 제공합니다.  
  - 사용자 및 리소스를 배치로 그룹화
  - 필요한 소프트웨어 패키지의 배포를 마이그레이션 일괄 처리를 통해 조정   
  - 최종 사용자에 대한 정보 교환 계획을 세우기 위한 지침 
  - 마이그레이션 일괄 처리, 오류 발생률 및 예상 헬프 데스크 지원의 규모 조정 
- 고객이 제공한 관련 정보에 따라 유형, 비즈니스 기능 및 대리인 액세스 권한을 기준으로 사용자 및 리소스 사서함을 일괄로 그룹화하기 위한 지침을 제공합니다.
    
## <a name="skype-for-business-online"></a>비즈니스용 Skype Online

- 비즈니스용 Skype 하이브리드 배포에서 사용자를 일괄로 마이그레이션하기 위한 지침을 제공합니다(연락처 목록 유지).
    
## <a name="office-365-proplus"></a>Office 365 ProPlus

- 다음에 대한 지침 및 지원을 제공합니다.  
  - 평가 및 계획은 업데이트의 초기 배포 및 관리에 대한 Microsoft의 모범 사례와 일치합니다.
  - Office 원격 분석 배포 및 구성 
  - 그룹 정책을 사용하는 Office 2013 이상 클라이언트에 대한 원격 분석 로깅 사용 
  - 이전 Office 클라이언트(Office 2003, Office 2007 및 Office 2010)에 대한 Office 원격 분석 에이전트 배포 
  - 원격 분석 프로세서 배포. 
    > [!NOTE]
    > 이를 위해서는 원격 분석 데이터를 저장할 파일 공유 위치와 처리된 데이터를 제출하기 위한 SQL Server 2005 이상이 실행되는 서버가 필요합니다. 
  
## <a name="your-responsibilities"></a>사용자의 업무

온보딩하는 동안 다음을 수행해야 합니다. [사용자의 업무](O365-your-responsibilities.md) 섹션에 정의된 업무 외에 다음 업무가 필요합니다. 
  
- 프로젝트 계획에 따라 리소스를 할당하고 관리합니다.  
- 시기 적절한 조치를 취하여 위험을 완화하고 고객, 파트너 프로젝트 관리자 및 FastTrack 관리자가 제기한 문제를 해결합니다.   
- 상황 보고서를 검토하고 적절하게 행동합니다.   
- 의사 결정 권한이 있는 운영 스폰서 또는 책임자에게 운영 위원회를 운영할 수 있는 책임을 부여합니다.  
- Microsoft 임원진 스폰서와 함께 일할 임원진 스폰서를 지정합니다.  
- 월별 운영 위원회 회의를 계획합니다.
    

  

