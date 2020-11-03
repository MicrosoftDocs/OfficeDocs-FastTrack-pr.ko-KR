---
title: 제품 및 기능
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 11/2/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Normal
ms.collection: FastTrack
description: 이 항목에는 FastTrack에서 지 원하는 작업 시나리오 및 시작 하기 전에 필요한 원본 환경에 대 한 자세한 정보가 포함 되어 있습니다. 현재 설정에 따라 성공적인 온 보 딩에 대 한 최소 요구 사항까지 원본 환경을 제공 하는 업데이트 관리 계획을 만드는 작업을 수행 합니다.
ms.openlocfilehash: 7071187e2bc2b52930a03b4bf9dabd4f717b88df
ms.sourcegitcommit: ca476a4195477d43a6f3a212bf27bfe473cc1ffa
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/02/2020
ms.locfileid: "48827108"
---
# <a name="products-and-capabilities"></a>제품 및 기능

## <a name="services-and-scenarios-supported-by-fasttrack"></a>FastTrack에서 지 원하는 서비스 및 시나리오

이 항목에는 FastTrack에서 지 원하는 작업 시나리오 및 시작 하기 전에 필요한 원본 환경에 대 한 자세한 정보가 포함 되어 있습니다. 현재 설정에 따라 성공적인 온 보 딩에 대 한 최소 요구 사항까지 원본 환경을 제공 하는 업데이트 관리 계획을 만드는 작업을 수행 합니다.

FastTrack은 먼저 핵심 기능 (모든 Microsoft Online 서비스에 대해 공통)과 온 보 딩 각 적합 한 서비스에 대 한 지침을 제공 합니다.

  - [일반](#general)
  - [Office 365](#office-365)
  - [Enterprise Mobility & 보안](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [Windows Virtual Desktop](#windows-virtual-desktop)
  - [앱 보증](#app-assure)
  - [새로운 Microsoft Edge](#the-new-microsoft-edge)

> [!NOTE]
> Office 365 미국 정부에 대한 원본 환경 기대치에 대한 정보는 [Office 365 미국 정부에 대한 원본 환경 기대치](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)를 참조하세요.
 
## <a name="general"></a>일반

<table>
<thead>
<tr class="header">
<th><strong>서비스</strong></th>
<th><strong>FastTrack 지침 세부 정보</strong></th>
<th><strong>원본 환경 기대치</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>핵심 온보딩</strong></td>
<td>  Microsoft는 서비스 프로 비전, 테 넌 트 및 id 통합이 포함 된 핵심 온 보 딩에 대 한 원격 지침을 제공 합니다. 또한 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">보안, 네트워크 연결 및 규정 준수에</a>대 한 설명을 비롯 하 여 Exchange Online, SharePoint Online, Microsoft 팀 등의 온 보 딩 서비스에 대 한 토대를 제공 하는 단계가 포함 되어 있습니다.  
  하나 이상의 적합한 서비스에 대한 온보딩은 핵심 온보딩이 완료되면 시작됩니다.
</li>
</ul>  

<strong> Id 통합 </strong>

여기서는 다음에 대 한 원격 지침을 제공 합니다.
<ul>
<li>Azure AD Connect 설치 및 구성 (단일/다중 포리스트) 및 라이선싱 (그룹 기반 라이선싱 포함)을 포함 하 여 azure Active Directory (Azure AD)에 대 한 동기화를 위한 온-프레미스 Active Directory Id를 준비 하는 중입니다.</li>
<li>그룹 기반 라이선싱 사용을 포함 하 여 대량 가져오기 및 라이선스를 비롯 한 클라우드 id 만들기</li>
<li>클라우드 여행, 암호 해시 동기화, 통과 인증 또는 AD FS (Active Directory Federation Services)에 대해 올바른 인증 방법을 선택 하 고 사용 하도록 설정 합니다.</li>
<li>단일 Active Directory 포리스트 및 id가 Azure AD Connect 도구와 동기화 된 고객에 대해 AD FS를 사용 하도록 설정 합니다. 이 경우 Windows Server 2012 R2 Active Directory Federation Services 2.0 이상이 필요 합니다.</li>
<li>암호 해시 동기화 또는 통과 인증을 사용 하 여 AD FS에서 Azure AD로 인증을 마이그레이션합니다.</li>
<li>통합 된 앱 (예를 들어, Azure AD 갤러리 소프트웨어 SaaS (as a service) 앱)을 AD FS에서 SSO (single sign-on)로 Azure AD로 마이그레이션합니다.</li>
<li>Azure AD 갤러리에서 SSO와 함께 SaaS 앱 통합을 사용 하도록 설정</li>
<li><a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">앱 통합 자습서 목록</a> 에 나열 된 미리 통합 된 SaaS 앱에 대해 자동 사용자 프로 비전을 사용 하도록 설정 합니다 (Azure AD 갤러리 SaaS 앱 및 아웃 바운드 프로 비전에만 국한 됨).  </li>
</td>

<td>  <strong>네트워크 지원 </strong>  
  <br>FastTrack 혜택의 일부로 클라우드 서비스에 연결 하기 위한 모범 사례를 제시 하 여 Microsoft 365의 최대 성능 수준을 확인 합니다.  
  
<strong>Active Directory 포리스트</strong> 다음 포리스트 구성을 사용 하 여 기능 포리스트 수준이 Windows Server 2003 이상으로 설정 되어 있습니다.
<ul>
<li>  단일 Active Directory 포리스트.  </li>
<li>  단일 Active Directory 계정 포리스트 및 리소스 포리스트(Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype) 토폴로지  </li>
<li>  여러 개의 Active Directory 계정 포리스트 및 리소스 포리스트(Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype) 토폴로지  </li>
<li>  포리스트 중 하나가 Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype가 있는 중앙 집중식 Active Directory 계정 포리스트인 여러 Active Directory 계정 포리스트  </li>
<li>  각각이 자체 Exchange 조직을 갖는 다중 Active Directory 계정 포리스트  </li>
<li>  필요한 경우 테 넌 트 구성 및 Azure Active Directory와의 통합에 필요한 작업입니다.   </li>
</ul>
  <strong>중요 한</strong>  <ul>
<li>  다중 포리스트 Active Directory 시나리오의 경우 Lync 2010, Lync 2013 또는 비즈니스용 Skype를 배포 하는 경우 Exchange와 동일한 Active Directory 포리스트에 배포 해야 합니다.  </li>
<li>  Exchange 다중 하이브리드 구성에서 여러 Exchange 조직이 포함 된 여러 Active Directory 포리스트를 구현 하는 경우 원본 포리스트 간의 공유 UPN (사용자 계정 이름) 네임 스페이스가 지원 되지 않습니다. Exchange 조직 간의 기본 SMTP 네임스페이스도 구분해야 합니다. 자세한 내용은 <a href="https://go.microsoft.com/fwlink/?linkid=845444">여러 Active Directory 포리스트를 사용한 하이브리드 배포</a>를 참조 하세요.  </li>
<li>  모든 다중 포리스트 구성의 경우 AD FS (Active Directory Federation Services) 배포가 범위를 벗어납니다. <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 파트너</a> 에 게 도움을 요청 하세요.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft 365 앱</strong></td>
<td>  다음에 대 한 원격 배포 지침을 제공 합니다.
<ul>
<li>  배포 문제 해결  </li>
<li>  Microsoft 365 관리 센터 및 Windows PowerShell을 사용하여 최종 사용자 및 디바이스 기반 라이선스 할당  </li>
<li>  간편 실행을 사용하여 Office 365 포털에서 Microsoft 365 앱 설치  </li>
<li>  iOS 또는 Android 장치에 Office Mobile 앱(에: Outlook Mobile, Word Mobile, Excel Mobile 및 PowerPoint Mobile) 설치  </li>
<li>  Office 365 배포 도구를 사용하여 업데이트 설정 구성  </li>
<li>  로컬 또는 클라우드 설치의 선택 및 설치  </li>
<li>  배포 패티지를 구성하기 위해 Office 사용자 지정 도구 또는 네이티브 XML을 사용하여 Office 배포 도구 구성 XML 작성  </li>
<li>  Microsoft Endpoint Configuration Manager를 사용하여 배포(Endpoint Configuration Manager 패키지 생성에 대한 지원 포함)  
  또한 이전 버전의 Office와 함께 작동 하는 매크로나 추가 기능을 사용 하 고 호환성 문제가 발생 하면 앱 보장 프로그램을 통한 추가 비용 없이 호환성 문제를 해결 하기 위한 지침을 제공 합니다. 자세한 내용은 <a href="#windows-10">Windows 10</a> 의 <strong>앱</strong> 부분을 확인 하세요. </li>
</ul></td>
<td><ul>
<li>  온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 및 Office의 시스템 요구 사항</a>에 정의 된 대로 최소 수준 이어야 합니다.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>네트워크 상태</strong></td>
<td>  조직의 사이트가 Microsoft의 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">네트워크 연결 원리</a>에 맞춰진 방식을 보여 주는 사용자 환경에서 주요 네트워크 연결 데이터를 가져오고 해석 하는 원격 지침을 제공 합니다. 이는 마이그레이션 속도, 사용자 환경, 서비스 성능 및 안정성에 직접적으로 영향을 주는 네트워크 점수를 강조 표시 합니다.  
  또한이 데이터로 강조 표시 된 수정 단계를 안내 하 여 네트워크 점수를 향상 시킬 수 있습니다.  </td>
<td><ul>
<li>  Microsoft 365 관리 센터 액세스  </li>
<li>  최신 버전의 Microsoft 365 앱이 필요 합니다.  </li>
<li>  위치 서비스 <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">는 Microsoft 365 관리 센터 (미리 보기)에서 네트워크 성능 권장 사항에</a>따라 사용 하도록 설정 됩니다.  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a>Office 365

<table>
<thead>
<tr class="header">
<th><strong>서비스</strong></th>
<th><strong>FastTrack 지침 세부 정보</strong></th>
<th><strong>원본 환경 기대치</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange Online</strong></td>
<td>  Exchange Online의 경우 조직에서 전자 메일을 사용할 수 있도록 준비 하는 프로세스를 안내 합니다. 정확한 단계는 원본 환경과 전자 메일 마이그레이션 계획에 따라 달라 집니다.  
  여기서는 다음에 대 한 원격 지침을 제공 합니다.
<ul>
<li>  Office 365에서 유효성이 검사된 모든 메일 사용이 가능한 도메인에 대해 EOP(Exchange Online Protection) 기능을 설정합니다.  </li>
<li>  메일 교환 (MX) 레코드를 Office 365로 가리키기  </li>
<li>  Office 365 ATP 기능이 구독 서비스의 일부일 경우이를 설정 하는 것입니다. 자세한 내용은이 표의 <strong>Office 365 Advanced Threat Protection</strong> 부분을 참조 하십시오.  </li>
<li>  구독 서비스의 일부로 Office 365에서 확인된 모든 메일 사용 가능 도메인에 대한 데이터 손실 방지(DLP) 기능 설정. MX 레코드가 Office 365를 가리키면 완료됩니다.</li>
<li>  구독 서비스의 일부로 Office 365에서 확인된 모든 메일 사용 가능 도메인에 대해 Office 365 메시지 암호화(OME)를 설정합니다. MX 레코드가 Office 365를 가리키면 완료됩니다.</li>
</ul>
  <strong>참고:</strong> MRS (Mailbox Replication service)는 온-프레미스 사서함의 IRM (정보 권한 관리) 전자 메일을 해당 Exchange Online 사서함으로 마이그레이션하기 위해 시도 합니다. 마이그레이션 후 보호된 콘텐츠를 읽는 기능은 클라이언트가 AD RMS(Active Directory Rights Managed Services) 서식 파일을 Azure RMS(Azure Rights Management Service)에 매핑하고 복사하는 방법에 따라 다릅니다.  
<ul>
<li>  방화벽 포트 구성  </li>
<li>  DNS 설정 (필요한 자동 검색, SPF (보낸 사람 정책 프레임 워크), DomainKeys 식별 된 메일 (DKIM), 도메인 기반 메시지 인증, 보고 및 적합성 (DMARC) 및 MX 레코드 (필요에 따라)를 포함 합니다.  </li>
<li>  원본 메시징 환경과 Exchange Online 간 전자 메일 흐름 설정(필요한 경우)  </li>
<li>  원본 메시징 환경에서 Office 365로 메일 마이그레이션 수행  </li>
<li>  사서함 클라이언트(Windows용 Outlook, 웹용 Outlook, iOS 및 Android용 Outlook) 구성  </li>
</ul>
  <strong>데이터 마이그레이션</strong>  <br>
Office 365 데이터 마이그레이션에 FastTrack 혜택을 사용 하는 방법에 대 한 자세한 내용은 <a href="https://docs.microsoft.com/fasttrack/data-migration">데이터 마이그레이션을</a>참조 하십시오.   
<td>  원본 환경은 다음 최소 수준 중 하나 여야 합니다.
<ul>
<li>  Exchange Server 2003 이후 버전을 사용하는 단일 또는 다중 Exchange 조직  </li>
<li>  단일 IMAP(Internet Message Access Protocol) 지원 전자 메일 환경  </li>
<li>  단일 G 제품군 환경(Gmail, 연락처 및 캘린더만)  </li>
<li>  다중 지역 기능에 대 한 자세한 내용은 <a href="https://go.microsoft.com/fwlink/?linkid=872776">Exchange Online의 다중 지역 기능</a>을 참조 하세요.  </li>
</ul>
Project for Office 365, Outlook for Windows, outlook for iOS 및 Android와 같은 온라인 클라이언트 소프트웨어, 비즈니스용 OneDrive 동기화 클라이언트, Power BI Desktop 및 비즈니스용 Skype는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office의 시스템 요구 사항</a>에 정의 된 대로 최소 수준 이어야 합니다.  </td>
</tr>
<tr class="even">
<td><strong>Microsoft 정보 거버넌스</strong></td>
<td>  여기서는 다음에 대 한 원격 지침을 제공 합니다.
<ul>
<li>  정보 거버넌스.  </li>
<li>  보존 레이블 및 정책.  </li>
<li>  레코드 관리.  </li>
<li>  삭제 정책.  </li>
<li>  커뮤니케이션 규정 준수.  </li>
<li>  참가자 위험 관리.  </li>
<li>  Advanced eDiscovery.  </li>
</ul></td>
<td><strong>핵심 온 보 딩</strong> 부분 외에, <a href="#general">일반적</a>으로 최소 시스템 요구 사항은 없습니다.</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Information Protection</strong></td>
<td>  여기서는 다음에 대 한 원격 지침을 제공 합니다.
<ul>
<li>  데이터 분류.  </li>
<li>  민감 정보 유형  </li>
<li>  민감도 레이블의 만들기  </li>
<li>  민감도 레이블의 적용  </li>
<li>  통합 레이블 구성  </li>
<li>  교육 가능한 분류자  </li>
<li>  콘텐츠 탐색기와 활동 탐색기를 사용하여 데이터 확인  </li>
<li>  정책을 사용하여 레이블 게시(수동 및 자동)  </li>
<li>  Microsoft Teams 채팅 및 채널에 대한 DLP(데이터 손실 방지) 정책 생성.  </li>
<li>  Microsoft Endpoint Manager에서 관리 하는 장치용 DLP 정책 만들기  </li>
</ul></td>
<td><strong>핵심 온 보 딩</strong> 부분 외에, <a href="#general">일반적</a>으로 최소 시스템 요구 사항은 없습니다.</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  여기서는 다음에 대 한 원격 지침을 제공 합니다.
<ul>
<li>  팀을 지원 하기 위해 Exchange Online, SharePoint Online, Office 365 그룹 및 Azure AD에 대 한 최소 요구 사항을 확인 합니다.  </li>
<li>  방화벽 포트 구성  </li>
<li>  DNS 설정.  </li>
<li>  Office 365 테넌트에서 팀 확인이 가능합니다.  </li>
<li>  사용자 라이선스 사용 또는 사용 안 함.  </li>
<li>  팀에 대 한 네트워크 평가:
<ul>
<li>  포트 및 끝점 검사  </li>
<li>  연결 품질 검사  </li>
<li>  대역폭 예상  </li>
</ul>
<ul>
<li>  팀 앱 정책 구성 (iOS 및 Android 앱에 대 한 팀 웹 앱, 팀 데스크톱 앱 및 팀)  </li>
</ul>
해당 하는 경우 다음에 대 한 지침도 제공 됩니다.
<ul>
<li>  Microsoft 팀 대화방 장치:  </li>
<ul>
<li>  <a href="https://go.microsoft.com/fwlink/?linkid=2066478">팀 장치 카탈로그</a>에 나열된 지원되는 전화 및 회의실 디바이스에 필요한 온라인 계정 생성.  </li>
<li>  인증 된 Microsoft 팀원 대화방 장치의 서비스 쪽 구성을 원격으로 지원 합니다.  </li>
<li>  오디오 회의 사용:  </li>
<li>  회의 브리지 기본 설정에 대한 조직 설정  </li>
<li>  회의 브리지를 라이선스가 있는 사용자에게 할당  </li>
</ul>
<li>  전화 시스템:
<ul>
<li>  클라우드 음성 기본 설정에 대한 조직 설정  </li>
<li>  통화 계획 지침 (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">사용 가능한 시장</a>):
<ul>
<li>  라이선스가 있는 사용자에게 번호 할당  </li>
<li>  UI(사용자 인터페이스)를 통해 최대 999개의 지역 번호 이식 지침  </li>
<li>  999개가 넘는 번호를 지원하는 지역 번호 이식 SR(서비스 요청)  </li>
</ul></li>
<li>  직접 라우팅 지침:
<ul>
<li>  파트너 호스팅 시나리오의 직접 라우팅 디자인 또는 최대 10 개의 사이트에 대 한 고객 배포 시나리오에 대 한 조직 설정 지침입니다.  </li>
<li> SBC (세션 경계 컨트롤러) 구성 검토 </li>

<li> 다이얼 플랜 구성을 통한 원격 지원 </li>

<li> 음성 경로 구성</li>

<li> 미디어 바이패스 및 로컬 미디어 최적화 </li>

</ul></li>
</ul></li>
<li>  권한 부여 팀 라이브 이벤트  </li>
<li>  조직 설정 및 Microsoft Stream에 통합  </li>
<li>  비즈니스용 Skype 전환에 대 한 지침입니다.  </li>
</ul></td>
<td><ul>
<li>  Id가 Office 365의 Azure AD에서 사용 되도록 설정 됩니다.  </li>
<li>  SharePoint Online에 대해 사용하는 사용자.  </li>
<li>  Exchange 사서함이 존재 합니다 (Exchange 하이브리드 구성에서는 온라인 및 온-프레미스).  </li>
<li>  Office 365 그룹에서 사용되도록 설정됩니다.  </li>
</ul>
  <strong>참고:</strong> 사용자가 SharePoint Online 라이선스를 사용 하 여 할당 되 고 사용 하도록 설정 되지 않은 경우 Office 365에 비즈니스용 OneDrive 저장소가 없습니다. 파일 공유가 채널에서 계속 작동 하지만 Office 365에서 비즈니스용 OneDrive 저장소를 사용 하지 않고 채팅에서 파일을 공유할 수 없습니다. 팀에서 SharePoint 온-프레미스를 지원 하지 않습니다.  <br>
  <strong>참고:</strong> 이상적인 상태는 모든 사용자가 사서함을 Exchange Online에 배치 하는 것입니다. 온-프레미스에 사서함이 있는 사용자는 Azure AD Connect를 통해 해당 id를 Office 365 디렉터리로 동기화 해야 합니다. 이러한 Exchange 하이브리드 고객의 경우 사용자의 사서함이 온-프레미스 인 경우 사용자는 커넥터를 추가 하거나 구성할 수 없습니다.  
  Microsoft Teams Windows 및 Mac 데스크톱 클라이언트용 설치 관리자는 <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>에서 다운로드할 수 있습니다.  </td>
</tr>
<tr class="odd">
<td><strong>Office 365 Advanced Threat Protection (ATP)</strong></td>
<td>  여기서는 다음에 대 한 원격 지침을 제공 합니다.
<ul>
<li>  안전한 링크, 안전한 첨부 파일 및 피싱 방지 사용.  </li>
<li>  자동화, 조사 및 대응 구성.  </li>
<li>  공격 시뮬레이터 사용.  </li>
<li>  보고 및 위협 분석.  </li>
</ul></td>
<td><strong>핵심 온 보 딩</strong> 부분 외에, <a href="#general">일반적</a>으로 최소 시스템 요구 사항은 없습니다.</td>
</tr>
<tr class="even">
<td><strong>iOS 및 Android용 Outlook</strong></td>
<td>  여기서는 다음에 대 한 원격 지침을 제공 합니다.
<ul>
<li>  Apple App Store를 Google Play에서 iOS 및 Android용 Outlook 다운로드  </li>
<li>  계정 구성 및 Exchange Online 사서함 액세스  </li>
<li>  Outlook mobile 보안 (자세한 내용은 <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Exchange Online에서 iOS 및 Android 용 Outlook 보안</a> 참조)  </li>
</ul></td>
<td><ul>
<li>  Id가 Office 365의 Azure AD에서 사용 되도록 설정 됩니다.  </li>
<li>  Exchange Online이 구성되고 라이선스가 할당됩니다.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  여기서는 다음에 대 한 원격 지침을 제공 합니다.
<ul>
<li>  Power BI 라이선스를 할당합니다.  </li>
<li>  Power BI Desktop 앱을 배포합니다.  </li>
</ul></td>
<td>Power BI Desktop과 같은 온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 및 Office의 시스템 요구 사항</a>에 정의 된 대로 최소 수준 이어야 합니다.</td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  여기서는 다음에 대 한 원격 지침을 제공 합니다.
<ul>
<li>  Project Online이 사용하는 기본 SharePoint 기능 확인  </li>
<li>  테넌트에 Project Online 서비스 추가(사용자에게 구독 추가 포함)  </li>
<li>  ERP(Enterprise 자원 그룹) 설정  </li>
<li>  첫 번째 프로젝트 만들기  </li>
</ul></td>
<td>Project for Office 365와 같은 온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 및 Office의 시스템 요구 사항</a>에 정의 된 대로 최소 수준 이어야 합니다.</td>
</tr>
<tr class="odd">
<td><strong>Project Online Professional 및 Premium</strong></td>
<td>  여기서는 다음에 대 한 원격 지침을 제공 합니다.
<ul>
<li>  배포 문제 해결  </li>
<li>  Microsoft 365 관리 센터 및 Windows PowerShell을 사용하여 최종 사용자 라이선스 할당  </li>
<li>  간편 실행을 사용하여 Office 365 포털에서 Project Online 데스크톱 클라이언트 설치  </li>
<li>  Office 365 배포 도구를 사용하여 업데이트 설정 구성  </li>
<li>  Project Online 데스크톱 클라이언트를 위한 단일 사이트에 배포 서버 설정(Office 365 배포 도구용 configuration.xml 파일을 만드는 지침 포함)  </li>
<li>  Project Online 데스크톱 클라이언트을 Project Online Professional 또는 Project Online Premium에 연결합니다.  </li>
</ul></td>
<td>Project for Office 365와 같은 온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 및 Office의 시스템 요구 사항</a>에 정의 된 대로 최소 수준 이어야 합니다.</td>
</tr>
<tr class="even">
<td><strong>SharePoint Online 및 비즈니스용 OneDrive</strong></td>
<td>  여기서는 다음에 대 한 원격 지침을 제공 합니다.
<ul>
<li>  DNS 설정.  </li>
<li>  방화벽 포트 구성  </li>
<li>  사용자 및 라이선스 프로비전  </li>
<li>SharePoint Online 관리자에 대해 사이트 만들기를 사용하도록 설정</li>
<li>사이트 모음 계획</li>
<li>콘텐츠 보호 및 권한 관리</li>
<li>SharePoint Online 기능 구성</li>
<li>  하이브리드 검색, 하이브리드 사이트, 하이브리드 분류, 콘텐츠 형식, 하이브리드 셀프 서비스 사이트 만들기(SharePoint Server 2013 전용), 확장된 앱 시작 관리자, 하이브리드 비즈니스용 OneDrive, 익스트라넷 사이트 등의 SharePoint 하이브리드 기능을 구성합니다.  </li>
<li>  마이그레이션 방식  </li>
</ul>
SharePoint 버전에 따라 다음과 같은 비즈니스용 OneDrive에 대 한 추가 지침이 제공 됩니다.
<ul>
<li>  통합 옵션 식별 및 온-프레미스 및 온라인 네트워크 인프라 및 대역폭 검토  </li>
<li>  SharePoint Online 2013 SP1 설치 (해당 하는 경우), 동기화 및 id 요구 사항 계획 및 구현 및 비즈니스용 OneDrive 동기화 클라이언트 식별  </li>
<li>  모든 사용자 또는 단계적 롤아웃에 대해 단일 롤아웃을 계획 및 구현 합니다.  </li>
<li>  라이선스 할당, 내 사이트 및 개인 문서 라이브러리를 Office 365 (SharePoint Online 2013에 해당)로 리디렉션, OneDrive에 대 한 액세스를 제어 하기 위한 대상 그룹 설정 (SharePoint Online 2013에 해당)  </li>
<li>알려진 폴더를 OneDrive로 리디렉션 또는 이동</li>
<li>  비즈니스용 OneDrive 클라이언트 동기화 배포  </li>
</ul>
  <strong>데이터 마이그레이션</strong>  <br>
Office 365 데이터 마이그레이션에 FastTrack 혜택을 사용 하는 방법에 대 한 자세한 내용은 <a href="https://docs.microsoft.com/fasttrack/data-migration">데이터 마이그레이션을</a>참조 하십시오.
</ul></td>
<td><br><strong>SharePoint 하이브리드의 경우:</strong>  
<ul>
<li>  SharePoint 하이브리드 구성에는 하이브리드 검색, 사이트, 분류, 콘텐츠 형식, 비즈니스용 OneDrive, 확장 앱 시작 관리자, 엑스트라넷 사이트 및 셀프 서비스 사이트 만들기가 온-프레미스에서 단일 대상 SharePoint Online 환경으로 연결 되는 구성 등이 포함 되어 있습니다.  </li>
</ul>
  <strong>참고:</strong> 셀프 서비스 사이트 만들기는 SharePoint 2013을 실행 하는 온-프레미스 서버와 범위에 포함 되어 있지 않습니다.  
<ul>
<li>  SharePoint 하이브리드를 사용 하도록 설정 하려면 온-프레미스 SharePoint Server 환경 2013, 2016 또는 2019 중 하나가 있어야 합니다.  </li>
</ul>
  <strong>참고:</strong> 온-프레미스 SharePoint 환경에서 SharePoint Server로의 업그레이드가 범위에 없습니다. <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 파트너</a> 에 게 도움을 요청 하세요. 자세한 내용은 <a href="https://go.microsoft.com/fwlink/?linkid=853548">SharePoint 하이브리드 기능에 대 한 최소 공개 업데이트 수준</a>를 참조 하세요<em>.</em>  <br>
  <strong>참고:</strong> 다중 지역 기능에 대 한 자세한 내용은 <a href="https://go.microsoft.com/fwlink/?linkid=831056">OneDrive 및 Office 365에서 SharePoint Online의 다중 지역 기능</a>을 참조 하세요<em>.</em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td><ul>
Yammer Enterprise 서비스를 사용 하도록 설정 하기 위한 원격 지침을 제공 합니다.  
</ul></td>
<td>온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 및 Office의 시스템 요구 사항</a>에 정의 된 대로 최소 수준 이어야 합니다.</td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Enterprise Mobility & 보안

<table>
<thead>
</tr>
<tr class="even">
<td><strong>Azure ad (Active Directory) 및 Azure AD Premium</strong></td>
<td>  Microsoft는 다음과 같은 시나리오에서 클라우드 id를 보호 하기 위한 원격 지침을 제공 합니다.  

 <br/>

<strong>보안 기본 인프라</strong>  </ul>
<ul>
<li>  MFA (Multi-factor Authentication) 및 azure MFA 및 셀프 서비스 암호 재설정 (SSPR)에 대 한 결합 된 등록을 포함 하 여 id에 대해 강력한 인증을 구성 하 고 사용 하도록 설정 합니다.  </li>
<li>  비 Azure AD Premium 고객의 경우 보안 기본값을 사용 하 여 id를 보호 하기 위한 지침이 제공 됩니다.  </li>
<li>  Azure AD premium 고객의 경우 조건부 액세스를 사용 하 여 id를 보호 하기 위한 지침이 제공 됩니다.  </li>
<li>  Azure AD 암호 보호를 통한 약한 암호 사용 감지 및 차단  </li>
<li>  Azure AD 응용 프로그램 프록시를 사용 하 여 온-프레미스 웹 앱에 대 한 원격 액세스 보호  </li>
<li>  Azure Id 보호를 통해 위험 기반 검색 및 재구성을 사용 하도록 설정  </li>
<li>  사용자 지정 브랜딩을 사용 하 여 로고, 텍스트 및 이미지를 비롯 한 사용자 지정 된 로그인 화면을 사용 하도록 설정  </li>
<li>  Azure AD B2B를 사용 하 여 게스트 사용자와 앱 및 서비스를 안전 하 게 공유 합니다.  </li>
<li>  RBAC (역할 기반 액세스 제어) 기본 제공 관리 역할을 사용 하 여 Office 365 관리자에 대 한 액세스를 관리 하 고 권한이 부여 된 관리자 계정의 수를 줄입니다.  </li>
<li>  하이브리드 Azure AD 조인 구성  </li>
<li>  Azure AD join을 구성 합니다.  </li>
</ul>
  
<strong>모니터링 및 보고</strong>  
<ul>
<li>  
  Azure AD Connect Health를 사용 하 여 AD FS, Azure AD Connect 및 도메인 컨트롤러에 대해 원격 모니터링을 사용 하도록 설정 합니다.  
  </li>
</ul>
  
<strong>지배</strong>  
<ul>
<li>  
  Azure AD 자격 증명 관리를 사용 하 여 확장에서 Azure AD id 및 액세스 수명 주기를 관리 합니다.
  </li>
<li>  
  Azure AD 액세스 검토를 사용 하 여 Azure AD 그룹 구성원, enterprise 앱 액세스 및 역할 할당 관리  
  </li>
<li>  
  Azure AD 사용 약관 검토  
  </li>
<li>  
  Azure AD 권한 Id 관리를 사용 하 여 권한 있는 관리자 계정에 대 한 액세스 관리 및 제어  
  </li>
</ul>
  
<strong>자동화 및 효율성 </strong>  
<ul>
<li>  
  Azure AD SSPR을 사용 하도록 설정 합니다.  
  </li>
<li>  사용자가 Azure AD 셀프 서비스 그룹 관리를 통해 자신의 클라우드 보안 또는 Office 365 그룹을 만들고 관리할 수 있도록 허용 합니다.  </li>
<li>  Azure AD 위임 된 그룹 관리를 사용 하 여 엔터프라이즈 앱에 대 한 위임 된 액세스 관리  </li>
<li>  Azure AD 동적 그룹을 사용 하도록 설정  </li>
<li>  컬렉션을 사용 하 여 내 앱 포털에서 앱 구성  </li>
</ul></td>
<td>Azure ad 및 Azure AD Premium 기능과의 통합을 방지 하는 식별 된 문제의 수정을 포함 하 여 온-프레미스 Active Directory 및 해당 환경이 Azure AD Premium에 대해 준비 되었습니다.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection(P2 또는 EMS E5)</strong></td>
<td>  다음 방법에 대 한 지침을 제공 합니다.
<ul>
<li>  테 넌 트를 활성화 및 구성 합니다.  </li>
<li>  레이블과 정책을 만들고 설정하기  </li>
<li>  문서에 정보 보호 적용하기  </li>
<li>  Azure Information Protection 클라이언트를 사용하여 Windows에서 실행 중인 Office 앱(Word, PowerPoint, Excel, Outlook 등)에서 자동으로 정보 분류 및 레이블 지정하기  </li>
<li>  Azure Information Protection 스캐너를 사용하여 보관 중인 파일 사용하기  </li>
<li>  Exchange Online 메일 흐름 규칙을 사용하여 전송 중인 전자 메일 모니터링하기  </li>
</ul>
Microsoft Azure RMS (권한 관리 서비스), Office 365 메시지 암호화 (OME) 및 DLP (데이터 손실 방지)를 사용 하 여 보호를 적용 하려는 경우에도 지침을 제공 합니다.  </td>
<td>  다음 작업을 수행 해야 합니다.
<ul>
<li>  Azure AD를 사용 합니다.  </li>
<li>  Windows 또는 iOS 사용 (다른 운영 체제는 범위를 벗어남)  
  </ul>
<strong>참고</strong>: 컴퓨터 및 모바일 장치를 Azure Information Protection을 지 원하는 <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">운영 체제</a> 에서 실행 해야 합니다.  
<li>  주 파일 공유 위치를 포함 합니다.  </li>
<strong>참고</strong>: 하이브리드 지원에는 AD RMS 커넥터가 필요 합니다. 
<li>  승인 된 분류 분류를 포함 합니다.  </li>
<li>  보호 된 키 관리에 대 한 규정 제한 사항을 이해 합니다.  </li>
</ul>
  
<strong>Azure Information Protection 스캐너</strong>  
  
다음 작업을 수행 해야 합니다.  
<ul>
<li>  Windows Server 2012 R2 또는 Windows Server 2016을 사용 합니다.  </li>
<li>  인터넷에 연결 되어 있어야 합니다.  </li>
<li>  로컬 또는 원격 인스턴스에 Microsoft SQL Server 2012 이상 버전을 포함 합니다.  </li>
<li>  온-프레미스 Active Directory에 대 한 서비스 계정을 만들고 Azure AD와 동기화 합니다.  </li>
<li>  AzInfoProtection.exe를 다운로드 했습니다.  </li>
<li>  자동 분류/보호를 위해 레이블을 구성 합니다.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Intune을 클라우드 기반 모바일 장치 관리 (MDM) 및 앱 및 장치용 MAM (모바일 앱 관리) 공급자로 사용할 수 있도록 준비 하는 방법에 대 한 지침을 제공 합니다. 정확한 단계는 원본 환경에 따라 다르며 모바일 장치와 모바일 앱 관리 요구 사항에 기반합니다. 해당 단계는 다음과 같습니다.
<ul>
<li>  최종 사용자에게 라이선스 부여  </li>
<li>  온-프레미스 Active Directory 또는 클라우드 id (Azure AD)를 사용 하 여 Intune에서 사용할 id 구성  </li>
<li>  Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기  </li>
<li>  다음을 포함 하 여 관리 요구에 따라 MDM 기관을 구성 합니다.
<ul>
<li>  Intune이 유일한 MDM 솔루션인 경우 Intune을 MDM 기관으로 설정  </li>
</ul></li>
<li>  MDM 지침 제공:
<ul>
<li>  MDM 관리 정책의 유효성을 검사하는 데 사용할 테스트 그룹 구성  </li>
<li>  다음과 같은 MDM 관리 정책 및 서비스 구성
<ul>
<li>  웹 링크 또는 딥 링크를 통해 지원 되는 각 플랫폼용 앱 배포  </li>
<li>  조건부 액세스 정책  </li>
<li>  조직의 기존 인증 기관, 무선 네트워크 또는 VPN 인프라가 있는 경우 전자 메일, 무선 네트워크 및 VPN의 배포 프로필입니다.  </li>
<li>  Intune 데이터 웨어하우스에 연결 합니다.  </li>
<li>  다음에 Intune 통합:
<ul>
<li>  Team Viewer for remote 지원 (Team Viewer 구독이 필요 함).  </li>
<li>  MTD (모바일 위협 방어) 파트너 솔루션 (MTD 구독이 필요 함)  </li>
<li>  통신 경비 관리 솔루션 (통신 경비 관리 솔루션 구독이 필요 함)  </li>
<li>  Microsoft Defender ATP (Windows E5 또는 Microsoft 365 E5 라이선스가 필요 함)  </li>
</ul></li>
<li>  각 지원되는 플랫폼의 장치를 Intune에 등록합니다.  </li>
</ul></li>
</ul></li>
<li>  앱 보호 지침 제공:
<ul>
<li>  지원되는 각 플랫폼에 대한 Intune 앱 보호 정책 구성  </li>
<li>  관리 되는 앱에 대 한 조건부 액세스 정책 구성  </li>
<li>  앞에서 설명한 MAM 정책을 사용 하 여 적절 한 사용자 그룹을 대상으로 지정 합니다.  </li>
<li>  관리 되는 앱 사용 현황 보고서 사용  </li>
</ul></li>
<li>  레거시 PC 관리의 마이그레이션 지침을 Intune MDM에 제공 합니다.  </li>
</ul>
  <strong>참고</strong>: 레거시 PC 관리는 더 이상 2020 이상에서 지원 되지 않습니다.  
</li>
</ul>
  
<strong>클라우드 연결</strong>  

  Intune을 사용 하 여 기존 Configuration Manager 환경을 클라우드로 연결 하는 과정을 안내 합니다. 정확한 단계는 원본 환경에 따라 다릅니다. 해당 단계는 다음과 같습니다.  
<ul>
<li>  최종 사용자에게 라이선스 부여  </li>
<li>  온-프레미스 Active Directory 및 클라우드 ID를 활용하여 Intune에서 사용할 ID 구성  </li>
<li>  Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기  </li>
<li>  하이브리드 Azure AD 조인의 설정 지침을 제공 합니다.  </li>
<li>  MDM 자동 등록에 대해 Azure AD를 설정 하는 방법에 대 한 지침을 제공 합니다.  </li>
<li>  클라우드 관리 게이트웨이를 설정하는 방법에 대한 지침을 제공합니다.  </li>
<li>  Intune으로 전환할 지원되는 작업 부하를 구성합니다.  </li>
<li>  Intune에서 등록된 디바이스에서 Configuration Manager 클라이언트를 설치합니다.  </li>
</ul> 

<strong>IOS 및 Android 용 Outlook mobile을 안전 하 게 배포</strong> 조직에서 iOS 및 Android 용 Outlook mobile을 안전 하 게 배포 하는 데 도움이 되는 지침을 제공 하 여 사용자에 게 필요한 모든 앱이 설치 되어 있는지 확인할 수 있습니다.  
  Intune을 사용 하 여 iOS 및 Android 용 Outlook mobile을 안전 하 게 배포 하는 단계는 원본 환경에 따라 달라 집니다. 여기에는 다음이 포함 될 수 있습니다.
<ul>
<li>  Apple App Store 또는 Google Play 스토어를 통해 iOS 및 Android, Microsoft Authenticator 및 Intune 회사 포털 앱을 다운로드 하는 경우  </li>
<li>  설정에 대 한 지침을 제공 합니다.
<ul>
<li>  Intune을 사용한 iOS 및 Android, Microsoft Authenticator 및 Intune 회사 포털 앱 배포를 위한 Outlook입니다.  </li>
<li>  앱 보호 정책  </li>
<li>  조건부 액세스 정책  </li>
<li>  앱 구성 정책  </li>
</ul></li>
</ul>
  
  <strong>참고</strong>: Fasttrack은 Exchange 모바일 장치 사서함 정책을 사용 하 여 IOS 및 Android 용 Outlook 보안을 지원 하지 않습니다. <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 파트너</a> 에 게 도움을 요청 하세요.  
  </td>
<td>  IT 관리자는 Intune을 사용 하 여 무선 네트워크 및 VPN 프로필을 배포할 때 계획을 수립할 때 기존 인증 기관, 무선 네트워크 및 VPN 인프라가 프로덕션 환경에서 이미 작동 하 고 있어야 합니다.  
  <strong>참고</strong>: fasttrack 서비스 혜택에는 Intune에 대해 인증 기관, 무선 네트워크, VPN 인프라 또는 Apple MDM 푸시 인증서를 설정 하거나 구성 하는 데 대 한 지원이 포함 되지 않습니다.  
 
  <strong>참고</strong>: 클라우드 연결 기능을 지원하는 데 필요한 최소 요구 사항에 맞게 Configuration Manager 사이트 서버 또는 Configuration Manager 클라이언트를 설정하거나 업그레이드하기 위한 지원은 FastTrack 서비스 혜택에 포함되지 않습니다. <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 파트너</a> 에 게 도움을 요청 하세요.

  <strong>Microsoft Defender ATP(Advanced Threat Protection)에 통합된 Intune</strong> 
 
  <strong>참고</strong>: MICROSOFT Defender ATP에 Intune을 통합 하 고 Windows 10 위험 수준 평가를 기반으로 장치 준수 정책을 만드는 방법에 대 한 지원을 제공 합니다. Microsoft는 구입, 라이선스 또는 정품 인증에 대 한 지원을 제공 하지 않습니다. <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 파트너</a> 에 게 도움을 요청 하세요.  
  
<strong>Windows Autopilot</strong> 
 
  IT 관리자는 하드웨어 공급 업체가 사용자를 대신하여 하드웨어 ID를 업로드하거나 Windows Autopilot 서비스로 업로드하는 방법으로 조직에 장치를 등록합니다.  
  
<strong>Intune을 사용 하 여 iOS 및 Android 용 Outlook을 안전 하 게 배포 </strong>  
<ul>
<li>  Office 365의 Azure AD에서 사용자 id를 사용할 수 있습니다.  </li>
<li>  사용자 라이선스를 할당 하 여 exchange Online 또는 하이브리드 Exchange를 구성 합니다.  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a>Windows 10

<table>
<thead>
<tr class="header">
<th><strong>서비스</strong></th>
<th><strong>FastTrack 지침 세부 정보</strong></th>
<th><strong>원본 환경 기대치</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  Windows 7 Professional 및 Windows 8.1 Professional에서 Windows 10 Enterprise로의 업그레이드에 대 한 지침을 제공 합니다.  
  여기서는 다음에 대 한 원격 지침을 제공 합니다.
<ul>
<li>  Windows 10 용도 이해  </li>
<li>  원본 환경 및 요구 사항 평가 (Microsoft Endpoint Configuration Manager가 Windows 10 배포를 지원 하기 위해 필요한 수준으로 업그레이드 되었는지 확인)  </li>
<li>  Microsoft Endpoint Configuration Manager 또는 Microsoft 365을 사용 하 여 Windows 10 Enterprise 및 Microsoft 365 앱을 배포 합니다.  </li>
<li>  Windows 10 앱 평가를 위한 옵션 권장  </li>
<li>  데스크톱 분석 배포 계획을 작성 하 여 데스크톱 분석 및 지침을 사용할 수 있도록 설정  </li>
<li>  Microsoft 365 앱 호환성 평가는 Configuration Manager에서 Office 365 준비 대시보드를 활용 하거나 Office 용 독립 실행형 준비 도구 키트 및 Microsoft 365 앱 배포에 도움이 됩니다.  </li>
<li>  성공적인 배포를 위한 최소 요구 사항을 충족 하기 위해 수행 해야 하는 작업에 대 한 재구성 검사 목록을 만듭니다.  </li>
<li>  필요한 장치 하드웨어 요구 사항을 충족 하는 경우 기존 장치에 대 한 업그레이드 지침을 Windows 10 Enterprise에 제공 합니다.  </li>
<li>  기존 배포 동작을 지원 하기 위한 업그레이드 지침 제공 FastTrack은 Windows 10으로의 준비된 업그레이드를 위한 지침을 권장하고 제공합니다. Windows 정리 이미지 설치 및 Windows Autopilot 배포 시나리오에서도 지침을 사용할 수 있습니다.  </li>
<li>  Windows 10 배포의 일부로 Configuration Manager를 사용 하 여 Microsoft 365 앱 배포   </li>
<li>  조직이 기존 Configuration Manager 환경 또는 Microsoft 365을 사용 하 여 Windows 10 Enterprise 및 Microsoft 365 앱을 최신 상태로 유지 하는 데 도움이 되는 지침을 제공 합니다.  </li>
</ul>
  <strong>다음은 범위를 벗어난 것입니다. </strong>  
<ul>
<li>  Configuration Manager를 현재 분기로 업그레이드.  </li>
<li>  Windows 10 배포용 사용자 지정 이미지 만들기.  </li>
<li>  Windows 10 배포용 배포 스크립트 만들기 및 지원  </li>
<li>  Windows 10 시스템을 BIOS에서 UEFI(Unified Extensible Firmware Interface)로 변환.  </li>
<li>  Windows 10 보안 기능 활성화.  </li>
<li>  PXE(Preboot Execution Environment) 부팅을 위해 WDS(Windows Deployment Services) 구성.  </li>
<li>  Windows 10 이미지를 캡처하여 배포하는 데 MDT(Microsoft Deployment Toolkit) 사용.  </li>
<li>  USMT(User State Migration Tool) 사용.  </li>
</ul>
이러한 서비스에 대 한 지원을 받으려면 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 파트너</a> 에 게 문의 하세요.  </td>
<td>  PC 업그레이드의 경우, 다음 요구 사항을 충족해야 합니다.
<ul>
<li>  원본 OS: Windows 7 Enterprise 또는 Professional, Windows 8.1 Enterprise 또는 Professional  </li>
<li>  장치: 데스크톱, 노트북 또는 태블릿 폼 팩터  </li>
<li>  대상 OS: Window 10 Enterprise  </li>
</ul>
인프라 업그레이드의 경우, 다음 요구 사항을 충족해야 합니다.
<ul>
<li>  Microsoft Endpoint Configuration Manager  </li>
<li>  Configuration Manager 버전은 Windows 10 대상 버전에서 지원 되어야 합니다. 자세한 내용은 <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager에서 Windows 10 지원</a>에서 Configuration Manager 지원 표를 참조하세요.  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP)는 엔터프라이즈 네트워크가 고급 위협을 방지, 탐지, 조사 및 대응하는 데 도움이 되도록 설계된 플랫폼입니다.  
  여기서는 다음에 대 한 원격 지침을 제공 합니다.
<ul>
<li>  끝점을 보호 하는 기술을 배포 합니다.  </li>
<li>  Endpoint protection 및 장치 제한 프로필 구성  </li>
<li>  OS 버전 및 장치 관리 (Intune, Microsoft 끝점 구성 관리자, Gpo (그룹 정책 개체) 및 타사 구성 포함) 및 Windows Defender AV 서비스의 상태 및 기타 끝점 보안 소프트웨어를 평가 합니다.  </li>
<li>  Windows AV 서비스 또는 기타 끝점 보안 소프트웨어의 상태를 평가 합니다.  </li>
<li>  프록시 및 방화벽을 평가 하면 네트워크 트래픽이 제한 됩니다.  </li>
<li>  온보드 끝점을 사용 하 여 ATP 에이전트 프로필을 배포 하는 방법을 설명 하는 Microsoft Defender ATP 서비스를 사용 하도록 설정 합니다.  </li>
<li>  배포 지침, 구성 지원 및 교육 내용:
<ul>
<li>  
  위협 및 취약성 관리.  
  </li>
<li>  
  공격 표면 감소.  
  </li>
<li>  
  차세대 보호.  
  </li>
<li>  
  끝점 감지 및 대응.  
  </li>
<li>  
  자동화된 조사 및 조치.  
  </li>
<li>  
  보안 점수.  
  </li>
</ul></li>
<li>  시뮬레이션 및 자습서 (연습 시나리오, 가짜 맬웨어 및 자동화 된 조사)를 검토 합니다.  </li>
<li>  보고 및 위협 분석 기능에 대해 간략하게 설명 합니다.  </li>
<li>  Office 365 ATP와 Microsoft Defender ATP 통합.  </li>
<li>  Microsoft Defender 보안 센터 포털 탐색.  </li>
<li>  다음과 같은 운영 체제
<ul>
<li>  
  Windows 10  
  </li>
<li>  
  Windows Server 2016  
  </li>
<li>  
  Windows Server 2019  
  </li>
<li>  
  Windows Server 2019 Core Edition  
  </li>
<li>  
  SAC (Windows Server Semi-Annual 채널) 버전 1803.  
  </li>
<li>  
  macOS 버전 10.13, 10.14 및 10.15  
  </li>
</ul>
</li>
</ul>
<strong>참고:</strong> 모든 Windows Server 버전은 System Center Configuration Manager 2012 (버전 1012 R2, 1511 또는 1602) 또는 Microsoft Endpoint Configuration Manager (버전 2002 이상)의 최신 버전으로 관리 해야 합니다. 

</li>
</ul>

<strong>다음은 범위를 벗어난 것입니다. </strong>  
<ul>
<li>  고객의 수정 활동에 대한 프로젝트 관리.  </li>
<li>  현장 지원.  </li>
<li>  지속적인 관리와 위협 대응.  </li>
<li>  다음 Microsoft Defender ATP 에이전트에 대한 온보딩 또는 구성:
<ul>
<li>  
  Windows Server 2008  
  </li>
<li>  
  Windows Server 2012  
  </li>
<li>  
  가속화.  
  </li>
<li>  
  모바일 장치 (Android 및 iOS)  
  </li>
</ul></li>
<li>  서버 온 보 딩 및 구성:
<ul>
<li>  
  오프 라인 통신을 위한 프록시 서버 구성  
  </li>
<li>  
  하위 수준 Configuration Manager 인스턴스 및 버전에 대 한 Configuration Manager 배포 패키지 구성  
  </li>
<li>  
  온 보 딩 서버가 Azure 보안 센터로 이동할 수 있습니다.  
  </li>
<li>  
  Configuration Manager에서 관리 되지 않는 서버  
  </li>
</ul></li>
<li>  macOS 온 보 딩 및 구성:
<ul>
<li>  
  수동 Intune 기반 배포  
  </li>
<li>  
  JAMF 기반 배포
  </li>
<li>  
  기타 MDM (모바일 장치 관리) 제품 기반 배포  
  </li>
<li>  
  수동 배포  
  </li>
</ul></li>
<li>  다음 공격 표면 감소에 대한 기능:
<ul>
<li>  
  하드웨어 기반 격리.  
  </li>
<li>  
  앱 컨트롤  
  </li>
<li>  
  악용 방지.  
  </li>
<li>  
  네트워크 방화벽.  
  </li>
</ul></li>
<li>  Microsoft 위협 전문가 등록 또는 구성.  </li>
<li>  구성 또는 교육 API 또는 SIEM (보안 정보 및 이벤트 관리) 연결 검토  </li>
<li>  MTP(Microsoft 위협 방지) 등록 또는 구성.  </li>
<li>  고급 헌팅에 대한 교육 또는 지침.  </li>
<li>  Kusto 쿼리 사용 또는 생성을 다루는 교육 또는 지침입니다.</li>
</li>
</ul>
이러한 서비스에 대 한 지원을 받으려면 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 파트너</a> 에 게 문의 하세요.  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a>Windows Virtual Desktop

<table>
<thead>
<tr class="header">
<th><strong>서비스</strong></th>
<th><strong>FastTrack 지침 세부 정보</strong></th>
<th><strong>원본 환경 기대치</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows Virtual Desktop</strong></td>
<td><p>Windows Virtual Desktop (데스크톱 및 앱 가상화 서비스)에 대 한 온 보 딩에 대 한 배포 지침을 제공 합니다. Windows 가상 데스크톱은 Windows 10 다중 세션 환경을 활용 하며 Microsoft 365에 대 한 통합 보안 및 관리를 포함 하는 Microsoft 365 for Enterprise 앱에 최적화 되어 있습니다.</p>
<p>여기서는 다음에 대 한 원격 지침을 제공 합니다.</p>
<ul>
<li>다음을 사용 하 여 Windows 10 Enterprise 다중 세션 및 엔터프라이즈 용 Microsoft 365 앱을 사용 하 여 Windows 가상 데스크톱 환경을 배포 합니다.
<ul>
<li>Azure 마켓플레이스 이미지</li>
<li>공유 이미지</li>
<li>ODT (Office 배포 도구 키트)</li>
</ul></li>
<li>FSLogix 구성:
<ul>
<li>프로필 컨테이너에 FSLogix 에이전트 배포</li>
<li>Office 컨테이너에 FSLogix 에이전트 배포</li>
<li>콘텐츠 제외로 FSLogix 폴더를 구성 합니다.</li>
</ul></li>
<li>Microsoft Edge 배포</li>
<li>Microsoft 팀 배포</li>
<li>Windows 가상 데스크톱 클라이언트를 사용 하 여 연결</li>
</ul>

<strong>다음은 범위를 벗어난 것입니다.</strong>
<ul>
<li>고객의 Windows 가상 데스크톱 배포에 대 한 프로젝트 관리입니다.</li>
<li>현장 지원.</li>
<li>타사 앱 가상화 및 배포</li>
<li>사용자 지정 이미지</li>
<li>VMware 및 Citrix와 관련 된 마이그레이션 및 시나리오</li>
<li>Linux 시나리오</li>
<li>사용자 프로필 변환 또는 마이그레이션</li>
</ul>
이러한 서비스에 대 한 지원을 받으려면 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 파트너</a> 에 게 문의 하세요.</td>
<td>다음이 포함 되어 있어야 합니다.
<ul>
<li><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows 가상 데스크톱 라이선스 요구 사항</a></li>
<li>Azure 네트워킹:
<ul>
<li>가상 네트워크 (VNET) 만들기 및 서브넷으로 만듭니다.</li>
<li>방화벽 및 네트워크 보안 그룹</li>
<li>VPN 및 Express 경로</li>
<li>온-프레미스에서 Azure로 라우팅</li>
<li>Windows 가상 데스크톱에 대 한 연결을 허용 하는 방화벽 규칙
</ul>
자세한 내용은 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> 지원 되는 원격 데스크톱 클라이언트</a>를 참조 하세요.
</ul>
<ul><li>Azure AD 일반 설정:
<ul>
<li>Id 전략 <i>(다음 세 가지 옵션 중 하나만 사용할 수 있습니다.)</i>
<ul>
<li>Azure에서 Azure AD Connect를 사용 하는 Active Directory입니다.</li>
<li>VPN 또는 Express를 통한 온-프레미스 Azure AD Connect를 사용 하는 Active Directory</li>
<li>AD DS (Active Directory 도메인 서비스)</li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a>App Assure


<table>
<thead>
<tr class="header">
<th><strong>서비스</strong></th>
<th><strong>FastTrack 지침 세부 정보</strong></th>
<th><strong>지원 되는 제품</strong></th>
</tr>
</thead>
<tbody>
</tr>
<tr class="even">
<td><strong>앱 보증</strong></td>
<td>  앱 보장은 Windows 10 및 Microsoft 365 Apps 앱 호환성과 관련 된 문제를 해결 하기 위해 설계 된 서비스입니다. 앱에 게 서비스를 요청할 경우 적합 한 구독을 추가 비용 없이 유효한 앱 문제를 해결 하는 데 도움이 됩니다. 또한 Windows Virtual Desktop 및 새 Microsoft Edge를 배포할 때 호환성 문제가 발생 하는 고객에 게 지침을 제공 하 고 호환성 문제를 해결 하는 데 필요한 모든 노력을 기울여야 합니다. 다음 Microsoft 제품에 배포 된 앱에 대 한 재구성 지원을 제공 합니다.
<ul>
<li>  <strong>Windows 10 </strong> (ARM64 장치 포함)</li>
<li> <strong>Microsoft 365 앱</strong>  </li>
<li>  <strong>새 Microsoft Edge-</strong> 배포 지침에 대 한 자세한 내용은 <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Microsoft Edge 채널 개요</a>를 참조 하세요.  </li>
<li>  <strong>Windows 가상 데스크톱</strong> - 자세한 내용은 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">Windows Virtual Desktop?</a> 및 <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">windows 10 ENTERPRISE 다중 세션 FAQ</a>를 참조 하세요.  </li>
</ul>

<strong>다음은 범위를 벗어난 것입니다. </strong>  
<ul>
<li>  Windows 10 및 Microsoft 365 앱에서 작동하거나 작동하지 않는 기능을 확인하기 위한 앱 인벤토리 및 테스트. 이 프로세스에 관한 자세한 지침을 보려면 <a href="https://go.microsoft.com/fwlink/?linkid=2080140">데스크톱 배포 센터</a>를 방문하세요. 더 심화된 업그레이드 준비 평가에 관심이 있으신 경우 <a href="https://go.microsoft.com/fwlink/?linkid=2053818">최신 데스크톱 평가에 관한 고객 요청</a> 양식을 작성하세요.</li>
<li>  타사 ISV 앱에서 Windows 10 호환성 및 지원 정책 연구 자세한 내용은 <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">데스크톱 분석</a>을 참조하세요.</li>
<li>앱 패키지 전용 서비스. 그렇지만 App Assure 팀은 고객 환경에 배포될 수 있도록 하기 위해 WIndows 10에 대해 수정한 앱을 패키지로 만듭니다.</li>
</ul>

<strong>고객 책임 포함</strong>  
<ul>
<li>  앱 목록 만들기.</li>
<li>  Windows 10 및 Microsoft 365 앱에서 앱의 유효성 검증.</li>
</ul>
<strong>참고:</strong>  Microsoft는 소스 코드를 변경할 수 없습니다. 그러나 사용자 앱의 소스 코드를 사용할 수 있는 경우 App Assure 팀이 앱 개발자에게 지침을 제공할 수 있습니다. 


  이러한 서비스에 대 한 지원을 받으려면 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 파트너</a> 에 게 문의 하세요.  </td>

</td>
<td><strong>Windows 10 및 Microsoft 365 앱</strong>
<ul>
<li>  
  Windows 7, Windows 8.1, Office 2010 및 Office 2013에서 작동하는 앱은 Windows 10 및 Microsoft 365 앱에서도 작동합니다.  
  </li>
</ul>
<strong>ARM의 Windows 10</strong>
<ul>
<li>  
Windows 7, Office 2010 이상 버전에서 작동 하는 앱은 ARM64 장치의 Windows 10 및 Microsoft 365 앱에서 작동 합니다. 
  </li>
</ul>
  <strong>참고:</strong> ARM 제외의 Windows 10에는 다음이 포함 됩니다.
<ul>
<li>  
 ARM에서 호환 되지 않는 소프트웨어 드라이버를 사용 하는 앱입니다.  
  </li>
<li>  
  OpenGL 또는 OpenCL를 사용 하는 앱입니다.   
  </li>
<li>  
  64 비트 (x64) 에서만 사용할 수 있는 앱  
  </li>
</ul>
<strong>새 Microsoft Edge</strong>
<ul>
<li>  
  웹 앱 또는 사이트가 Internet Explorer 11, 지원되는 버전의 Google Chrome 또는 모든 버전의 Microsoft Edge에서 작동하는 경우 새로운 Microsoft Edge에서도 작동합니다.  
  </li>
<li>  
  웹이 계속 해 서 발전 함에 따라, <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">Microsoft Edge에 대 한 알려진 사이트 호환성 변경 사항에 대 한</a>이 게시 된 목록을 검토 하세요.  
  </li>
</ul>
  <strong>Windows 가상 데스크톱 </strong>  
<ul>
<li>  
  Windows Server RDSH (원격 데스크톱 세션 호스트)에서 실행되는 가상화된 앱도 Windows Virtual Desktop의 일부로 Windows 10 Enterprise 멀티 세션에서 실행됩니다.  
  </li>
<li>  
  모든 Windows 7 또는 Windows 10 VDI (가상 데스크톱 인프라) 환경 에서도 실행 되는 앱은 windows 7 Enterprise 및 windows 10 Enterprise에서 실행 됩니다.  
  </li>
<li>  
  Windows 7 또는 Windows 10 클라이언트 장치에서 실행되는 앱도 Windows Virtual Desktop의 일부로 Windows 7 Enterprise 및 Windows 10 Enterprise에서 실행됩니다.  
  </li>
</ul>
  <strong>참고:</strong> Windows 10 Enterprise 다중 세션 호환성 및 제한은 다음과 같습니다.
<ul>
<li>  
  제한된 하드웨어 리디렉션.  
  </li>
<li>  
  A/V-집약적인 앱은 줄어든 용량으로 실행될 수 있습니다.  
  </li>
<li>  
  16비트 앱은 64비트 Windows Virtual Desktop에서 지원되지 않습니다.  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="the-new-microsoft-edge"></a>새로운 Microsoft Edge


<table>
<thead>
<tr class="header">
<th><strong>서비스</strong></th>
<th><strong>FastTrack 지침 세부 정보</strong></th>
<th><strong>원본 환경 기대치</strong></th>
</tr>
</thead>
<tbody>
</tr>
<tr class="even">
<td><strong>Microsoft Edge</strong> (Windows 10 Enterprise 고객용)</td>
<td><ul>
<li>  Microsoft는 Windows 10 Enterprise에 새 Microsoft Edge를 배포 하는 방법에 대 한 원격 배포 지침과 호환성 지원을 제공 합니다 (microsoft endpoint Configuration Manager 또는 Intune).  </li>
<li>  Microsoft Edge 구성 (그룹 정책 또는 Intune 앱 구성 및 앱 정책 사용)  </li>
<li>  Internet Explorer 모드에서 사용 해야 할 수 있는 사이트 목록을 인벤토리에 작성 합니다.  </li>
<li>  기존 엔터프라이즈 사이트 목록에서 Internet Explorer 모드를 사용 하도록 설정  
  또한 Internet Explorer 또는 Google Chrome에서 작동 하는 웹 앱 이나 사이트가 있고 호환성 문제가 발생 하는 경우에는 추가 비용 없이 문제를 해결 하기 위한 지침을 제공 합니다. 자세한 내용은 <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">앱</a> 을 확인 하세요.  </li>
</ul>

<strong>다음은 범위를 벗어난 것입니다. </strong>  
<ul>
<li>고객의 Microsoft Edge 배포에 대한 프로젝트 관리입니다.</li>
<li>  현장 지원.</li>

</td>
<td></td>
</tr>
</tbody>
</table>
