---
title: Office 365 미국 정부에 대한 원본 환경 기대치
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 2/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: None
ms.collection: FastTrack
description: FastTrack 센터 혜택에는 원본 환경과 일정 수준의 통합을 설정할 수 있도록 지침을 제공합니다(예를 들어, Office 365로 이동하려는 서비스가 원본 환경에 이미 있는 경우).
ms.openlocfilehash: af713b6ec75c3f52ed4b92a8fb96e3e1987b1861
ms.sourcegitcommit: cf630a48697177b9cce6c0fbc67a7e7a0b752167
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/03/2021
ms.locfileid: "50416579"
---
# <a name="source-environment-expectations-for-office-365-us-government"></a>Office 365 미국 정부에 대한 원본 환경 기대치

FastTrack 센터 혜택에는 원본 환경과 일정 수준의 통합을 설정할 수 있도록 지침을 제공합니다(예를 들어, Office 365로 이동하려는 서비스가 원본 환경에 이미 있는 경우).
  
> [!NOTE]
> 통합이 필요한 경우 원본 환경은 해당 응용 프로그램의 수준 이상이어야 합니다. 
  
다음 표에는 온보딩을 위해 기존 원본 환경에서 요구되는 조건이 나와 있습니다.

|**작업**|**원본 환경 요구 조건**|
|:-----|:-----|
|핵심 온보딩 | 다음 포리스트 구성을 사용하며 포리스트 기능 수준이 Windows Server 2003 이상으로 설정된 Active Directory 포리스트:  <br/>      단일 Active Directory 포리스트.  <br/>    단일 Active Directory 계정 포리스트 및 리소스 포리스트(Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype) 토폴로지  <br/>  여러 개의 Active Directory 계정 포리스트 및 리소스 포리스트(Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype) 토폴로지  <br/>  포리스트 중 하나가 Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype가 있는 중앙 집중식 Active Directory 계정 포리스트인 여러 Active Directory 계정 포리스트  <br/>  각각이 자체 Exchange 조직을 갖는 다중 Active Directory 계정 포리스트 <br/> <br/> **참고**  *여러 포리스트 Active Directory 시나리오의 경우 Lync 2010, Lync 2013 또는 비즈니스용 Skype를 배포할 때 동일한 Active Directory를 Exchange로 배포해야 합니다.*   <br/>  <br/>      **참고**  *다중 Active Directory 포리스트를 Exchange 다중 하이브리드 구성의 여러 Exchange 조직으로 구현하는 경우 원본 포리스트 간의 공유된 UPN(사용자 계정 이름) 네임스페이스는 지원되지 않습니다. Exchange 조직 간의 기본 SMTP 네임스페이스도 구분해야 합니다. 자세한 내용은 [다중 Active Directory 포리스트로 하이브리드 배포](https://go.microsoft.com/fwlink/?linkid=845444)를 참조하세요.*     <br/>   <br/>   **참고**  *모든 다중 포리스트 구성에서 ADFS 배포는 FastTrack 센터 혜택을 받지 않습니다.*           |
|Exchange Online 온보딩 | 사용자 환경은 다음 최소 수준 중 하나여야 합니다.  <br/>  Exchange Server 2003 이후 버전을 사용하는 단일 또는 다중 Exchange 조직  <br/>  단일 IMAP(Internet Message Access Protocol) 지원 전자 메일 환경  <br/>  단일 G 제품군 환경(Gmail, 연락처 및 캘린더만)             |
|SharePoint Online 및 비즈니스용 OneDrive 온보딩  | **SharePoint 하이브리드**  <br/>  SharePoint 하이브리드 구성에는 온-프레미스에서 단일 대상 SharePoint Online 환경으로 연결된 하이브리드 검색, 사이트, 분류, 콘텐츠 형식, 비즈니스용 OneDrive, 확장된 앱 시작 관리자, 엑스트라넷 사이트 및 셀프 서비스 사이트 만들기 구성이 포함됩니다. SharePoint 하이브리드를 사용하려면 다음 온-프레미스 SharePoint Server 환경 중 하나가 있어야 합니다.  <br/> <br/> **_SharePoint Server 2013_ _ 하이브리드 콘텐츠 형식에 대한 *<br/> 2017년 6월 PU(공개 업데이트) 자세한 내용은 [Configure hybrid SharePoint taxonomy and hybrid content types을 참조하세요.](https://go.microsoft.com/fwlink/?linkid=853547)  셀프 서비스 사이트 만들기 구성에 대한 2017년 3월 PU입니다. 하이브리드 셀프 서비스 사이트 만들기는 <br/> SharePoint Server 2013에서만 지원됩니다. 자세한 내용은 하이브리드 셀프 서비스 [사이트 만들기를 참조하세요.](https://go.microsoft.com/fwlink/?linkid=846015)  <br/>하이브리드 세분화가 있는 2016년 11월 이후 PU입니다. 자세한 내용은 하이브리드 SharePoint 세분화 계획을 [참조하세요.](https://go.microsoft.com/fwlink/?linkid=844867)  다른 모든 하이브리드 구성 시나리오에 대한 <br/> 2016년 7월 이후 PU입니다.  <br/> <br/> _* 참고***SharePoint Server 2013 하이브리드 시나리오는 SharePoint Server 2013에서만 지원됩니다. 이러한 시나리오는 SharePoint Foundation 2013에서 지원되지 않습니다.*    <br/>   <br/>    ***SharePoint Server 2016** _  <br/>  하이브리드 콘텐츠 형식에 대한 2017년 6월 PU입니다. 자세한 내용은 [하이브리드 SharePoint 분류 및 하이브리드 콘텐츠 형식 구성](https://go.microsoft.com/fwlink/?linkid=853547)을 참조하세요.  <br/>  하이브리드 분류가 있는 2016년 11월 PU(기능 팩 1)입니다. 자세한 내용은 [하이브리드 SharePoint 분류 계획](https://go.microsoft.com/fwlink/?linkid=844867)을 참조하세요.  <br/>  다른 모든 하이브리드 구성 시나리오에 대한 2016년 7월 이후 PU입니다.  <br/><br/> _ *참고* *   *SharePoint Server 2013 또는 SharePoint Server 2016으로의 사내 SharePoint 환경 업그레이드는 FastTrack 센터 혜택에서 제공되지 않습니다. 자세한 내용은 [SharePoint](https://go.microsoft.com/fwlink/?linkid=853548)* 하이브리드 기능에 대한 최소 공개 업데이트 수준을 참조하세요.             |
|비즈니스용 Skype Online 온보딩  | **네트워크 평가**  <br/>  포트 및 끝점 검사  <br/>  연결 품질 검사  <br/>  대역폭 예상  <br/><br/>  **Lync 하이브리드**  <br/>  단일 온-프레미스 Active Directory 포리스트  <br/>  Lync 2013 관리 도구 또는 비즈니스용 Skype 2015 관리 도구가 있는 Lync 2010 서버 환경 및 Lync 2010 에지 서버 역할  <br/>  Lync 2013 서버 환경 및 Lync 2013 에지 서버 역할  <br/><br/>  **비즈니스용 Skype 온라인 하이브리드**  <br/>  단일 온-프레미스 Active Directory 포리스트  <br/>  단일 Active Directory 계정 포리스트 이상 및 리소스 포리스트(Exchange 및/또는 비즈니스용 Skype) 토폴로지  <br/>  Exchange 및/또는 비즈니스용 Skype에 중앙 집중식 Active Directory 계정 포리스트 하나가 포함된 여러 Active Directory 계정 포리스트  <br/>  비즈니스용 Skype 에지 서버 역할을 포함하는 비즈니스용 Skype Server 2015 환경  <br/><br/> **참고**  *이 추가 서비스는 분할 도메인(하이브리드) 작업의 구성 및 유효성 검사용이고, 온-프레미스 구성 요소(예: Lync 2013 관리 도구 또는 Lync 2013/비즈니스용 Skype 온라인 서버 또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype 에지 서버) 도입을 포함하지 않습니다.*    <br/><br/>        **회의실 장치**  <br/>  [비즈니스 솔루션용 Skype 카탈로그](https://go.microsoft.com/fwlink/?LinkId=615775)의 회의실 시스템에 나열된 지원되는 회의실 장치에 필요한 온라인 계정을 만듭니다.  <br/><br/>  **오디오 회의 사용**  <br/>  회의 브리지 기본 설정에 대한 조직 설정  <br/>  회의 브리지를 라이선스가 있는 사용자에게 할당  <br/><br/>  **전화 시스템 및 통화 계획 사용(GCC High 또는 DoD 계획에서는 사용할 수 없는 미국만 해당)**  <br/>  클라우드 음성 기본 설정에 대한 조직 설정  <br/>  라이선스가 있는 사용자에게 번호 할당  <br/>  UI(사용자 인터페이스)를 통해 최대 999개의 지역 번호 이식 지침  <br/>  999개가 넘는 번호를 지원하는 지역 번호 이식 SR(서비스 요청)  <br/><br/>  **비즈니스용 Skype 모임 브로드캐스트 지침 온보드 사용(GCC High 또는 DoD 계획에서는 사용할 수 없습니다)**  <br/>  모임 브로드캐스트 서비스가 있는 페더레이션에 대한 조직 설정   |
|Microsoft Teams 온보드(GCC High 또는 DoD 계획에서는 사용할 수 없습니다) | ID가 Office 365용 Azure Active Directory에서 사용되도록 설정됩니다.  <br/>  SharePoint Online에 대해 사용하는 사용자.  <br/>  Exchange 사서함이 존재합니다(Exchange 하이브리드 구성에 있는 온라인 및/또는 온-프레미스).  <br/>  Office 365 그룹에서 사용되도록 설정됩니다.  <br/><br/> **참고**  *사용자에게 SharePoint Online 라이선스가 할당되거나 사용되도록 설정되지 않은 경우 Office 365에서 비즈니스용 OneDrive 저장소가 제공되지 않습니다. 파일 공유는 채널에서 계속 작동하지만, Office 365에 비즈니스용 OneDrive 저장소가 없으면 사용자는 채팅 중에 파일을 공유할 수 없습니다. Microsoft Teams는 SharePoint 온-프레미스를 지원하지 않습니다.*   <br/> <br/>       **참고**  *ExchangeOnline에 속한 사서함이 있는 모든 사용자 이상적인 상태입니다. 온-프레미스에 속한 사서함이 있는 사용자는 ID를 Azure Active Directory Connect를 통해 Office 365 디렉터리로 동기화해야 합니다. 이러한 Exchange 하이브리드 고객 중에 사용자 사서함이 온-프레미스인 경우 사용자는 커넥터를 추가하거나 구성할 수 없습니다.*          |
| 다음을 포함하는 온보딩 서비스:  <br/>  *Exchange Online  <br/>  SharePoint Online  <br/>  비즈니스용 OneDrive  <br/>  비즈니스용 Skype Online Microsoft Teams Power BI Project Online Yammer Microsoft  <br/>  <br/>  <br/>  <br/>  <br/>  365 앱  <br/>*   |Project for Office 365, Outlook 클라이언트, 비즈니스용 OneDrive 동기화 클라이언트, Power BI Desktop, 비즈니스용 Skype 등의 온라인 클라이언트 소프트웨어는 [Office용 시스템 요구 사항](https://go.microsoft.com/fwlink/?LinkID=723597)에 정의된 대로 최소 수준이어야 합니다.  <br/> Microsoft Teams Windows 및 Mac 데스크톱 클라이언트용 설치 관리자는 [https://go.microsoft.com/fwlink/?linkid=839411](https://go.microsoft.com/fwlink/?linkid=839411)에서 다운로드할 수 있습니다.   |
