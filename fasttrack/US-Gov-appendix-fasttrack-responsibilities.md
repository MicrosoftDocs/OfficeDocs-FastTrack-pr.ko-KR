---
title: Office 365 US 정부에 대 한 FastTrack 책임
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 1/03/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: None
ms.collection: FastTrack
description: FastTrack Specialist는 온보딩하는 동안 다음을 수행해야 합니다.
ms.openlocfilehash: 6ac727d55ba8d5653fb9ebffa95b7c3c4a104f70
ms.sourcegitcommit: d7f4c9eafe7855c6ae02c2bd0fe3b700c458007c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/02/2020
ms.locfileid: "40929296"
---
# <a name="fasttrack-responsibilities-for-office-365-us-government"></a>Office 365 US 정부에 대 한 FastTrack 책임

FastTrack Specialist는 온보딩하는 동안 다음을 수행해야 합니다.
  
## <a name="general"></a>일반

- Microsoft는 사용자의 성공적인 계획 개발 및 구현과 단계 설명에 나와 있는 필수 구성 작업을 원격으로 지원합니다.
- 사용 가능한 문서, 소프트웨어 도구, 관리 콘솔 및 스크립트를 제공하여 구성 작업 및 성공적인 계획 리소스를 줄이거나 제거할 수 있는 지침을 제공합니다.   
    
## <a name="initiate-phase"></a>시작 단계

- 사용자와 협의하면서 서비스에 대한 사용자의 의도, 조직의 목표 및 사용 계획을 파악합니다. 
- Microsoft 팀와 같은 Office 365 공동 작업 서비스를 사용하여 온보딩을 시작합니다. 
- 온보딩할 적합한 서비스를 정의합니다. 
    
## <a name="assess-phase"></a>평가 단계

- 성공적인 계획 통화를 실시하여 성공적인 사용자 채택을 위한 지침을 제공합니다.  
- 관리 개요를 제공합니다.  
- 다음에 대한 지침을 제공합니다. 
  - DNS(Domain Name System), 네트워크 및 인프라가 필요합니다.  
  - 클라이언트 요구(인터넷 브라우저, 클라이언트 운영 체제, 모바일 장치 및 서비스 요구)
  - 사용자 ID 및 프로비전 
  - 구매한 후 온보딩의 일부로 정의한 적합한 서비스 사용
  - 성공적인 서비스 채택 및 가치 지원   
- 재구성 작업을 위한 일정을 지정합니다.
- 재구성 검사 목록을 제공합니다.   
- 다음을 포함하여 기존 SharePoint Server 2013 또는 SharePoint Server 2016 인프라를 평가합니다.  
  - SharePoint Online 하이브리드의 필수 구성 요소  
  - SharePoint Online 하이브리드 기능에 대한 온-프레미스 인프라 준비  
  - 필수 SharePoint Online 끝점에 대한 액세스 
  - 하이브리드 비즈니스용 OneDrive의 대상 그룹    
- 다음을 포함하여 기존 Lync 또는 비즈니스용 Skype 온라인 인프라를 평가합니다.  
  - 지원되는 비즈니스용 Skype 클라이언트 배포 전략  
  - 끝점 액세스  
  - 연결 품질  
  - 대역폭 예상  
  - 분할 도메인 서버 구성을 지원하는 필수 구성 요소  
  - 비즈니스용 Skype 온라인으로 이동하려는 식별된 사용자의 준비 상태  
- 다음과 같은 메시징 인프라를 평가합니다.   
  - 전반적인 메일 흐름 및 라우팅 원칙  
  - 클라이언트 액세스(기존에 게시된 클라이언트-액세스 끝점 포함)  
  - 통합을 위한 원본 메시징 환경 요건 
- FastTrack 센터 데이터 마이그레이션 서비스를 사용 하 고 자격을 충족 하는 경우 데이터 마이그레이션을 제공 합니다.
    
## <a name="remediate-phase"></a>재구성 단계

- 합의된 일정에 따라 전화 회의를 실시하여 재구성 활동 및 성공적인 계획의 진행 상태를 검토합니다.   
- 평가 도구를 실행하여 문제를 식별하고 수정하며 결과를 해석할 수 있도록 안내합니다.
    
## <a name="enable-phase"></a>사용 단계

다음에 대한 지침을 제공합니다. 
- 성공적인 계획의 진행 상태를 평가하고 사용자에게 필요한 추가 지원 결정    
- Office 365 테넌트 활성화
- TCP/IP 프로토콜 및 방화벽 포트 구성   
- 적합한 서비스에 대한 DNS 구성   
- Office 365에 대한 연결 유효성 검사   
- 온-프레미스 Active Directory를 Azure Active Directory에 연결:   
  - 필요한 경우 AD DS(Active Directory 도메인 서비스) 및 Office 365 간에 디렉터리 동기화 서버 설치   
  - 필요한 경우 Azure Active Directory Connect 도구를 사용하여 Office 365(Azure Active Directory)에 대한 암호 동기화(암호 해시)를 구성합니다.  
  - 단일 및 다중 포리스트 환경:
      - 필요한 경우 Azure Active Directory 통과 인증을 구성 합니다 (GCC High 또는 DoD 요금제에서는 사용할 수 없음).
      - 필요한 경우 Azure Active Directory 원활한 SSO (Single Sign-on)를 구성 합니다 (GCC High 또는 DoD 요금제에서는 사용할 수 없음).
    > [!NOTE]
    > 사용자의 Active Directory 포리스트 간에 포리스트 트러스트가 있는 경우 및 이름 접미사 라우팅이 올바르게 구성된 경우 다중 포리스트 환경에 Azure Active Directory 통과 인증이 지원됩니다. 로그인 요청에 대한 고가용성을 제공하기 위해 여러 온-프레미스 서버에 추가 에이전트가 설치될 수 있습니다. 자세한 내용은 [Azure Active Directory 통과 인증: 빠른 시작](https://go.microsoft.com/fwlink/?linkid=860094) 및 [Azure Active Directory 원활한 Single Sign-On: 빠른 시작](https://go.microsoft.com/fwlink/?linkid=860095)을 참조하세요.[!NOTE]
    > 통과 인증 제한에 대한 자세한 내용은 [Azure Active Directory 통과 인증: 현재 제한](https://go.microsoft.com/fwlink/?linkid=860356)을 참조하세요.[!NOTE]
    > 원활한 SSO 문제에 대한 자세한 내용은 [Azure Active Directory 원활한 Single Sign-On 문제 해결](https://go.microsoft.com/fwlink/?linkid=841926)을 참조하세요. 
- 페더레이션 ID가 대상인 경우 단일 포리스트: 
  - 필요한 경우 단일 사이트 내결함성 구성에서 Office 365를 통해 로컬 도메인 인증을 받기 위한 AD FS 설치 및 구성  
  - 필요한 경우 AD FS 인프라를 인트라넷에 게시하기 위한 WAP 설치 및 구성 
    > [!NOTE]
    > 모든 다중 포리스트 구성에 대한 ADFS 배포는 다루지 않습니다. 
- 배포된 경우 SSO 기능 테스트   
- 성공적인 서비스 채택 및 가치 지원
    
## <a name="exchange-online"></a>Exchange Online

다음에 대한 지침을 제공합니다. 
- DNS 레코드 만들기 또는 업데이트    
- 원본 메시징 시스템과 Office 365 환경 간에 전자 메일 라우팅을 사용하도록 설정    
- 유효성이 확인된 모든 메일 사용이 가능한 도메인에 대해 Exchange Online Protection 기능(구독에서 사용할 수 있는 경우 Exchange Online Advanced Threat Protection 포함) 구성 및 MX 레코드가 Office 365를 가리키는지 확인   
- 단일 온-프레미스 Exchange 조직과 Office 365 *또는* 여러 온-프레미스 Exchange 조직과 Office 365 간에 하이브리드 설정 구성 
- Exchange Online을 사용 하 여 UM (통합 메시징) 설정 (UM은 GCC DoD 요금제에서는 사용할 수 없음) 
    
데이터 마이그레이션 책임에 대한 자세한 내용은 [데이터 마이그레이션](O365-data-migration.md)을 참조하세요.
  
## <a name="sharepoint-online"></a>SharePoint Online

다음에 대한 지침을 제공합니다.
- 라이선스를 비롯한 사용자 프로비전 설정   
- SharePoint Online 관리자에 대해 사이트 만들기를 사용하도록 설정   
- 사이트 모음 계획   
- 콘텐츠 보호 및 권한 관리   
- 개인 사이트 및 소셜 기능을 사용하도록 설정   
- SharePoint Online 기능 구성    
- FastTrack 센터 데이터 마이그레이션 서비스를 사용하고 자격을 충족하는 경우 데이터 마이그레이션을 제공  
- SharePoint Online 하이브리드온-프레미스 SharePoint 팜 인프라 구성 평가    
- 도구 및 자동화를 사용하여 다음을 수행합니다. 
  - 온-프레미스 클라우드 검색 서비스 응용 프로그램을 구성합니다.    
  - SharePoint 온-프레미스 및 클라우드 환경 간에 트러스트를 구성합니다.   
- SharePoint Online 하이브리드 기능을 사용하도록 온-프레미스 SharePoint 사이트 구성
    
## <a name="onedrive-for-business"></a>비즈니스용 OneDrive

다음에 대한 지침을 제공합니다. 
- 온-프레미스 SharePoint 버전 및 통합 옵션 식별    
- 동기화 및 ID 옵션 식별   
- 다음 출시 옵션 중에서 선택:   
  - Just-in-time 출시  
  - 미리 구성된 출시(순차적 및 단계적)   
- 비즈니스용 OneDrive 배포를 위한 온-프레미스 환경 준비:  
  - 올바른 비즈니스용 OneDrive 동기화 클라이언트 식별 
  - DNS, 네트워크 포트 및 방화벽 구성   
- 최종 사용자 라이선스 할당   
- SharePoint Online 대상 그룹을 설정하여 비즈니스용 OneDrive를 사용하는 대상 사용자 제어    
- 데스크톱에 비즈니스용 OneDrive 동기화 클라이언트 배포   
- SharePoint Online 하이브리드 비즈니스용 OneDrive 리디렉션(SharePoint 2013 및 SharePoint 2016만) 구성 방법  
- FastTrack 센터 데이터 마이그레이션 서비스가 사용되며 자격을 충족하는 경우 데이터 마이그레이션
    
## <a name="skype-for-business-online"></a>비즈니스용 Skype Online

다음에 대한 지침을 제공합니다.
- Office 365에 대한 비즈니스용 Skype ID 프로비저닝   
- Office 365에 대한 온라인 회의, IM(인스턴트 메시징) 및 현재 상태 기능을 사용하도록 설정  
- 지원되는 채팅방 시스템 장치에 연결되는 계정 만들기(최대 10개의 계정)    
- Lync 하이브리드 또는 비즈니스용 Skype 온라인 하이브리드 시나리오를 지원하는 분할 도메인 서버 환경을 구성합니다(해당하는 경우).   
- 오디오 회의 사용:   
  - 회의 브리지 기본 설정에 대한 조직 설정   
  - 회의 브리지를 라이선스가 있는 사용자에게 할당 
- 전화 시스템 사용 (GCC High 또는 DoD 요금제에서는 사용할 수 없음):  
  - 전화 시스템 및 통화 계획 온보딩 사용(사용할 수 있는 시장) 
  - 라이선스가 있는 사용자에게 번호 할당  
  - UI를 통해 최대 999개의 지역 번호 이식 지침  
  - 999개가 넘는 번호를 지원하는 지역 번호 이식 SR  
- 비즈니스용 Skype 모임 브로드캐스트 사용 (GCC High 또는 DoD 요금제에서는 사용할 수 없음):  
  - 비즈니스용 Skype 모임 브로드캐스트 지침을 온보딩하여 사용하도록 설정  
  - 모임 브로드캐스트 서비스가 있는 페더레이션에 대한 조직 설정
    
## <a name="microsoft-teams"></a>Microsoft Teams

다음에 대한 지침을 제공합니다.
- 최소 요구 사항 확인.   
- 방화벽 포트 구성  
- DNS 설정.  
- Office 365 테넌트에서 Microsoft 팀 확인이 가능합니다   
- 사용자 라이선스 사용 또는 사용 안 함.  
- Microsoft 팀 클라이언트 배포.    
- IT 전문가 및 관리자를 위한 기능. 
- 주요 제품 기능.  
- 고객 성공 템플릿.
    
## <a name="power-bi"></a>Power BI

다음에 대한 지침을 제공합니다.
- Power BI 구독 계획 검토    
- Power BI 서비스를 추가합니다.    
- Power BI Desktop 앱 다운로드
    
## <a name="project-online"></a>Project Online

다음에 대한 지침을 제공합니다.  
- 구독 계획 검토  
- 기본 SharePoint 기능 확인    
- Project Online 서비스 추가  
- ERP 동기화를 포함하여 Project Online에 사용자 추가  
- 프로젝트를 만들어 기본 Project Online 기능 확인
    
## <a name="yammer-enterprise"></a>Yammer Enterprise

단일 Yammer Basic 네트워크를 단일 Yammer Enterprise 네트워크로 변환하는 방법에 대한 지침을 제공합니다.

> [!NOTE]
> Yammer Enterprise는 Office 365 US 정부의 구성 요소가 아니며, GCC에서 Office 365에 사용이 허가 된 각 사용자의 독립 실행형 제공으로는 비용 없이 취득 될 수 있습니다. 이 제안은 현재 기업 계약과 엔터프라이즈 구독 계약에 따라 Office 365 GCC를 구매한 고객만으로 제한 됩니다. Yammer는 GCC High 또는 DoD 요금제에서는 사용할 수 없습니다.
  
## <a name="office-365-proplus"></a>Office 365 ProPlus

다음에 대한 지침을 제공합니다.
- 배포 문제 해결   
- [Microsoft 365 관리 센터](https://go.microsoft.com/fwlink/?linkid=2032704) 및 Windows PowerShell을 사용하여 최종 사용자 라이선스 할당  
- 간편 실행을 사용하여 Office 365 포털에서 Office 365 ProPlus 설치   
- iOS, Android 또는 Windows Mobile 장치에 Office Mobile 앱(에: Outlook Mobile, Word Mobile, Excel Mobile 및 PowerPoint Mobile) 설치   
- Office 2016 배포 도구 또는 그룹 정책 템플릿을 사용하여 업데이트 설정 구성   
- Office 365 ProPlus를 위한 단일 사이트에 배포 서버 설정(Office 365 배포 도구용 configuration.xml 파일을 만드는 지침 포함)   
- System Center Configuration Manager를 사용하여 배포(System Center Configuration Manager 패키지 생성에 대한 지원 포함)

    


