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
# <a name="products-and-capabilities"></a>제품 및 기능

## <a name="services-and-scenarios-supported-by-fasttrack"></a>FastTrack에서 지원되는 서비스 및 시나리오

이 항목에서는 FastTrack이 지원되는 작업 시나리오와 시작하기 전에 필요한 원본 환경 기대치에 대해 자세히 설명합니다. 현재 설정에 따라, 성공적인 온보딩에 필요한 최소 한도로 원본 환경을 가져오는 재구성 계획을 만드세요.

FastTrack은 핵심 기능(모든 Microsoft Online Services에 공통된)을 사용한 다음 적격한 각 온보딩 서비스를 사용하는 데 도움이 되는 지침을 제공합니다.

  - [일반](#general)
  - [Office 365](#office-365)
  - [Enterprise Mobility & 보안](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [App Assure](Win-10-app-assure.md)
  - [새로운 Microsoft Edge](Win-10-microsoft-edge.md)

> [!NOTE]
> Office 365 미국 정부에 대한 원본 환경 기대치에 대한 정보는 [Office 365 미국 정부에 대한 소스 환경 기대치를 참조하세요.](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)
 
## <a name="general"></a>일반

<table>
<thead>
<tr class="header">
<th><strong>서비스</strong></th>
<th><strong>FastTrack 지침 세부 정보</strong></th>
<th><strong>원본 환경 기대</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>핵심 온보딩</strong></td>
<td>  Microsoft는 서비스 프로비전, 테넌트 및 ID 통합이 포함되는 핵심 온보딩에 대한 원격 지침을 제공합니다. 또한 보안, 네트워크 연결 및 규정 준수에 대한 토론을 포함하여 Exchange Online, SharePoint Online 및 Microsoft Teams와 같은 온보딩 서비스에 기초 사안을 제공하기 위한 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">단계도 포함됩니다.</a>  
  하나 이상의 적합한 서비스에 대한 온보딩은 핵심 온보딩이 완료되면 시작됩니다.
</li>
</ul>  

<strong> ID 통합 </strong>

다음에 대한 원격 지침이 제공됩니다.
<ul>
<li>Azure AD Connect 설치 및 구성(단일 또는 다중 포리스트) 및 라이선스(그룹 기반 라이선싱 포함)를 포함하여 Azure Directory(Azure AD)에 동기화를 위한 온-프레미스 Active Directory ID 준비.</li>
<li>그룹 기반 라이선싱 사용을 포함하여 대량 가져오기 및 라이선스를 포함한 클라우드 ID 만들기</li>
<li>클라우드 이동 과정에 올바른 인증 방법, 암호 해시 동기화, 통과 인증 또는 AD FS(Active Directory Federation Services)를 원하는지 확인하고 사용하도록 설정.</li>
<li>단일 Active Directory 포리스트 및 ID가 Azure AD Connect 도구와 동기화된 고객에 대해 AD FS를 사용하도록 설정 이 작업을 Windows Server 2012 R2 Active Directory Federation Services 2.0 이상이 필요합니다.</li>
<li>암호 해시 동기화 또는 통과 인증을 사용하여 AD FS에서 Azure AD로 인증을 마이그레이션하는 경우</li>
<li>SSO(Single Sign-On)에 대해 AD FS에서 Azure ADFS로 의지와 미리 통합된 앱(예: Azure AD 갤러리 소프트웨어-A-Service(SaaS) 앱)을 AD FS에서 Azure AD로 마이그레이션</li>
<li>Azure AD 갤러리에서 SSO와 SaaS 앱 통합 사용</li>
<li>앱 통합 자습서 목록에 나열된 사전 통합된 SaaS 앱에 대해 자동 사용자 프로비저닝을 활성화합니다(Azure AD 갤러리 SaaS 앱 및 아웃바운드 프로비저닝으로만 제한됨). <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a>  </li>
</td>

<td>  <strong>네트워크 사용 </strong>  
  <br>FastTrack 혜택의 일부로 클라우드 서비스에 연결하여 Microsoft 365의 최고 수준의 성능을 보장하시기 바라는 것이 좋습니다.  
  
<strong>Active Directory 포리스트</strong> 이러한 기능의 포리스트 수준은 다음 포리스트 구성을 사용하여 Windows Server 2003 이상으로 설정되어 있습니다.
<ul>
<li>  단일 Active Directory 포리스트.  </li>
<li>  단일 Active Directory 계정 포리스트 및 리소스 포리스트(Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype) 토폴로지  </li>
<li>  여러 개의 Active Directory 계정 포리스트 및 리소스 포리스트(Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype) 토폴로지  </li>
<li>  포리스트 중 하나가 Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype가 있는 중앙 집중식 Active Directory 계정 포리스트인 여러 Active Directory 계정 포리스트  </li>
<li>  각각이 자체 Exchange 조직을 갖는 다중 Active Directory 계정 포리스트  </li>
<li>  테넌트를 구성하고 필요한 경우 Azure Active Directory와 통합하는 데 필요한 작업입니다.   </li>
</ul>
  <strong>중요:</strong>  <ul>
<li>  다중 포리스트 Active Directory 시나리오의 경우 Lync 2010, Lync 2013 또는 비즈니스용 Skype를 배포할 때 Exchange와 동일한 Active Directory를 배포해야 합니다.  </li>
<li>  여러 Exchange 조직이 Exchange 다중 하이브리드 구성의 여러 Exchange 조직으로 포리스트를 구현하는 경우 원본 포리스트 간의 공유된 UPN(사용자 계정 이름) 네임스페이스는 지원되지 않습니다. Exchange 조직 간의 기본 SMTP 네임스페이스도 구분해야 합니다. 자세한 내용은 <a href="https://go.microsoft.com/fwlink/?linkid=845444">Active Directory 포리스트가 여러 개인 하이브리드 배포를 참조하세요.</a>  </li>
<li>  모든 다중 포리스트 구성에서 AD FS(Active Directory Federation Services) 배포는 다범위를 벗어나는 것입니다. 이에 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">대한 지원을</a> 받기만 하면 Microsoft 파트너에 문의하세요.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft 365 앱</strong></td>
<td>  다음에 대한 원격 배포 지침이 제공됩니다.
<ul>
<li>  배포 문제 해결  </li>
<li>  Microsoft 365 관리 센터 및 Windows PowerShell을 사용하여 최종 사용자 및 디바이스 기반 라이선스 할당  </li>
<li>  간편 실행을 사용하여 Office 365 포털에서 Microsoft 365 앱 설치  </li>
<li>  iOS 또는 Android 장치에 Office Mobile 앱(에: Outlook Mobile, Word Mobile, Excel Mobile 및 PowerPoint Mobile) 설치  </li>
<li>  Office 365 배포 도구를 사용하여 업데이트 설정 구성  </li>
<li>  로컬 또는 클라우드 설치의 선택 및 설치  </li>
<li>  배포 패티지를 구성하기 위해 Office 사용자 지정 도구 또는 네이티브 XML을 사용하여 Office 배포 도구 구성 XML 작성  </li>
<li>  Microsoft Endpoint Configuration Manager를 사용하여 배포(Endpoint Configuration Manager 패키지 생성에 대한 지원 포함)  
  또한 이전 버전의 Office와 함께 작동한 매크로나 추가 기능을 사용하고 호환성 문제가 발생하는 경우 App Assure 프로그램을 통해 추가 비용 없이 호환성 문제를 해결하는 지침을 제공합니다. 자세한 내용은 <a href="#windows-10">Windows 10의</a> <strong>App Assure</strong> 부분을 참조하세요. </li>
</ul></td>
<td><ul>
<li>  온라인 클라이언트 소프트웨어는 Microsoft 365 및 Office의 시스템 요구 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">사항에 정의된 적어도 수준으로 있어야 합니다.</a>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>네트워크 상태</strong></td>
<td>  Microsoft는 조직의 사이트가 네트워크 연결의 Microsoft에서 정도를 어떻게 정도 조정하고 운영하는지를 보여주는 환경의 주요 네트워크 연결 데이터를 얻고 고석할 때 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">원격 지침을 제공합니다.</a> 이렇게 하면 마이그레이션 결과, 사용자 환경, 서비스 성능 및 안정성에 직접적으로 영향을 미치는 네트워크 점수가 강조 표시됩니다.  
  또한 네트워크 점수를 개선하는 데 도움이 되는 이 데이터가 강조하는 수정 단계를 안내합니다.  </td>
<td><ul>
<li>  Microsoft 365 관리 센터 액세스  </li>
<li>  Microsoft 365 앱의 업데이트 버전이 필요합니다.  </li>
<li>  <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 관리 센터(미리 보기)에서 네트워크 성능 권장 사항에 따나는 위치 서비스입니다.</a>  </li>
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
<th><strong>원본 환경 기대</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange Online</strong></td>
<td>  Exchange Online의 경우 조직에서 전자 메일 사용 준비를 완료하도록 안내합니다. 정확한 단계는 원본 환경 및 전자 메일 마이그레이션 계획에 따라 다릅니다.  
  다음에 대한 원격 지침이 제공됩니다.
<ul>
<li>  Office 365에서 유효성이 검사된 모든 메일 사용이 가능한 도메인에 대해 EOP(Exchange Online Protection) 기능을 설정합니다.  </li>
<li>  Office 365를 가리키도록 메일 교환(MX) 레코드를 설정합니다.  </li>
<li>  구독 서비스의 일부인 경우 Office 365 ATP 기능을 설정합니다. 자세한 내용은 이 표의 <strong>Office 365 Advanced Threat Protection</strong> 부분을 참조하세요.  </li>
<li>  구독 서비스의 일부로 Office 365에서 확인된 모든 메일 사용 가능 도메인에 대한 데이터 손실 방지(DLP) 기능 설정. MX 레코드가 Office 365를 가리키면 완료됩니다.</li>
<li>  구독 서비스의 일부로 Office 365에서 확인된 모든 메일 사용 가능 도메인에 대해 Office 365 메시지 암호화(OME)를 설정합니다. MX 레코드가 Office 365를 가리키면 완료됩니다.</li>
</ul>
  <strong>참고:</strong> MRS(사서함 복제 서비스)는 온-프레미스 사서함의 IRM(정보 권한 관리) 전자 메일을 해당 Exchange Online 사서함으로 마이그레이션하려고 시도합니다. 마이그레이션 후 보호된 콘텐츠를 읽는 기능은 클라이언트가 AD RMS(Active Directory Rights Managed Services) 서식 파일을 Azure RMS(Azure Rights Management Service)에 매핑하고 복사하는 방법에 따라 다릅니다.  
<ul>
<li>  방화벽 포트 구성  </li>
<li>  필요한 자동 검색, SPF(보낸 사람 정책 프레임워크), DKIM(Domain-Based Message Authentication, Reporting and Conformance) 및 MX 레코드(필요에 따라)를 비롯한 DNS 설정  </li>
<li>  원본 메시징 환경과 Exchange Online 간 전자 메일 흐름 설정(필요한 경우)  </li>
<li>  원본 메시징 환경에서 Office 365로 메일 마이그레이션 수행  </li>
<li>  사서함 클라이언트(Windows용 Outlook, 웹용 Outlook, iOS 및 Android용 Outlook) 구성  </li>
</ul>
  <strong>데이터 마이그레이션</strong>  <br>
Office 365로의 데이터 마이그레이션에 대한 FastTrack 혜택을 사용하는 방법에 대한 자세한 내용은 데이터 <a href="https://review.docs.microsoft.com/fasttrack/data-migration">마이그레이션을 참조하세요.</a>   
<td>  원본 환경은 다음 최소 수준 중 하나로 포함해야 합니다.
<ul>
<li>  Exchange Server 2003 이후 버전을 사용하는 단일 또는 다중 Exchange 조직  </li>
<li>  단일 IMAP(Internet Message Access Protocol) 지원 전자 메일 환경  </li>
<li>  단일 G 제품군 환경(Gmail, 연락처 및 캘린더만)  </li>
<li>  다중 위치 기능에 대한 자세한 내용은 <a href="https://go.microsoft.com/fwlink/?linkid=872776">Exchange Online의 다중 위치 기능을 참조하세요.</a>  </li>
</ul>
Project for Office 365, Windows용 Outlook, iOS 및 Android용 Outlook, 비즈니스용 OneDrive 동기화 클라이언트, Power BI Desktop, 비즈니스용 Skype 등의 온라인 클라이언트 소프트웨어는 Microsoft 365 Office의 시스템 요구 사항에 정의된 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">것처럼 최소 수준에 있어야 합니다.</a>  </td>
</tr>
<tr class="even">
<td><strong>Microsoft 정보 거버넌스</strong></td>
<td>  다음에 대한 원격 지침이 제공됩니다.
<ul>
<li>  정보 거버넌스.  </li>
<li>  보존 레이블 및 정책.  </li>
<li>  레코드 관리.  </li>
<li>  삭제 정책.  </li>
<li>  커뮤니케이션 규정 준수.  </li>
<li>  내부자 위험 관리.  </li>
<li>  Advanced eDiscovery.  </li>
</ul></td>
<td>일반적으로 핵심 <strong>온보딩 부분과</strong> <a href="#general">관련하여 최소</a>시스템 요구 사항은 없습니다.</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Information Protection</strong></td>
<td>  다음에 대한 원격 지침이 제공됩니다.
<ul>
<li>  데이터 분류.  </li>
<li>  중요한 정보 유형  </li>
<li>  민감도 레이블 만들기.  </li>
<li>  민감도 레이블 적용.  </li>
<li>  통합 레이블 구성.  </li>
<li>  훈훈 가능한 분류자  </li>
<li>  콘텐츠 탐색기와 활동 탐색기를 사용한 사용자 데이터 확인.  </li>
<li>  정책을 사용하여 레이블을 게시합니다(수동 및 자동).  </li>
<li>  Microsoft Teams 채팅 및 채널용 DLP(데이터 손실 방지) 정책 만들기  </li>
</ul></td>
<td>일반적으로 핵심 <strong>온보딩 부분과</strong> <a href="#general">관련하여 최소</a>시스템 요구 사항은 없습니다.</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  다음에 대한 원격 지침이 제공됩니다.
<ul>
<li>  Teams를 지원하기 위해 Exchange Online, SharePoint Online, Office 365 그룹 및 Azure AD에서 최소 요구 사항 확인  </li>
<li>  방화벽 포트 구성  </li>
<li>  DNS 설정.  </li>
<li>  Office 365 테넌트에서 팀 확인이 가능합니다.  </li>
<li>  사용자 라이선스 사용 또는 사용 안 함.  </li>
<li>  Teams에 대한 네트워크 평가:
<ul>
<li>  포트 및 끝점 검사  </li>
<li>  연결 품질 검사  </li>
<li>  대역폭 예상  </li>
</ul>
<ul>
<li>  Teams 앱 정책 구성(Teams 웹 앱, Teams 데스크톱 앱, iOS 및 Android용 Teams 앱)  </li>
</ul>
해당하는 경우 다음에 대한 지침도 제공합니다.
<ul>
<li>  Microsoft Teams 룸 장치:  </li>
</ul>
<ul>
<li>  Teams 장치 카탈로그에 나열된 지원되는 전화 및 회의실 장치에 필요한 온라인 <a href="https://go.microsoft.com/fwlink/?linkid=2066478">계정 생성.</a>  </li>
</ul>
<ul>
<li>  오디오 회의 사용:  </li>
</ul>
<ul>
<li>  회의 브리지 기본 설정에 대한 조직 설정  </li>
<li>  회의 브리지를 라이선스가 있는 사용자에게 할당  </li>
</ul>
<ul>
<li>  전화 시스템:
<ul>
<li>  클라우드 음성 기본 설정에 대한 조직 설정  </li>
<li>  통화 플랜 지침(사용 가능한<a href="https://go.microsoft.com/fwlink/?linkid=2066478">시장):</a>
<ul>
<li>  라이선스가 있는 사용자에게 번호 할당  </li>
<li>  UI(사용자 인터페이스)를 통해 최대 999개의 지역 번호 이식 지침  </li>
<li>  999개가 넘는 번호를 지원하는 지역 번호 이식 SR(서비스 요청)  </li>
</ul></li>
<li>  직접 라우팅 지침:
<ul>
<li>  파트너 호스팅 시나리오 또는 단일 사이트에 대한 고객 배포 시나리오의 직접 라우팅 디자인을 위한 조직 설정 지침  </li>
</ul></li>
</ul></li>
<li>  권한 부여 팀 라이브 이벤트  </li>
<li>  조직 설정 및 Microsoft Stream에 통합  </li>
</ul></td>
<td><ul>
<li>  ID가 Office 365용 Azure AD에서 사용하도록 설정된 경우  </li>
<li>  SharePoint Online에 대해 사용하는 사용자.  </li>
<li>  Exchange 사서함이 존재합니다(Exchange 하이브리드 구성에 있는 온라인 및 온-프레미스).  </li>
<li>  Office 365 그룹에서 사용되도록 설정됩니다.  </li>
</ul>
  <strong>참고:</strong>   사용자가 할당되고 SharePoint Online 라이선스로 사용하도록 설정되지 않은 경우 Office 365의 비즈니스용 OneDrive 저장소가 제공되지 않습니다. 채널에서 계속 파일을 공유할 수 있지만, 사용자는 Office 365에 비즈니스용 OneDrive 저장소가 없이 채팅에서 파일을 공유할 수 없습니다. Teams는 SharePoint 온-프레미스를 지원하지 않습니다.  <br>
  <strong>참고:</strong>   Exchange Online에 있는 사서함이 있는 모든 사용자 이상적 상태입니다. 온-프레미스에 속한 사서함이 있는 사용자는 ID를 Azure AD Connect를 통해 Office 365 디렉터리로 동기화해야 합니다. 이러한 Exchange 하이브리드 고객의 경우 사용자 사서함이 온-프레미스인 경우 사용자는 커넥터를 추가하거나 구성할 수 없습니다.  
  Microsoft Teams Windows 및 Mac 데스크톱 클라이언트용 설치 관리자는 다음에서 다운로드할 수  <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> 있습니다.  </td>
</tr>
<tr class="odd">
<td><strong>Office 365 Advanced Threat Protection (ATP)</strong></td>
<td>  다음에 대한 원격 지침이 제공됩니다.
<ul>
<li>  안전한 링크, 안전한 첨부 파일 및 피싱 방지 사용.  </li>
<li>  자동화, 조사 및 대응 구성.  </li>
<li>  공격 시뮬레이터 사용.  </li>
<li>  보고 및 위협 분석.  </li>
</ul></td>
<td>일반적으로 핵심 <strong>온보딩 부분과</strong> <a href="#general">관련하여 최소</a>시스템 요구 사항은 없습니다.</td>
</tr>
<tr class="even">
<td><strong>iOS 및 Android용 Outlook</strong></td>
<td>  다음에 대한 원격 지침이 제공됩니다.
<ul>
<li>  Apple App Store를 Google Play에서 iOS 및 Android용 Outlook 다운로드  </li>
<li>  계정 구성 및 Exchange Online 사서함 액세스  </li>
<li>  Outlook 모바일 보호(자세한 <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">내용은 Exchange Online의 iOS 및 Android 보안</a> 참조)  </li>
</ul></td>
<td><ul>
<li>  ID가 Office 365용 Azure AD에서 사용하도록 설정된 경우  </li>
<li>  Exchange Online이 구성되고 라이선스가 할당됩니다.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  다음에 대한 원격 지침이 제공됩니다.
<ul>
<li>  Power BI 라이선스를 할당합니다.  </li>
<li>  Power BI Desktop 앱을 배포합니다.  </li>
</ul></td>
<td>Power BI Desktop과 같은 온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 및 Office의 시스템 요구 사항에 정의된 것처럼 최소 수준으로 설치되어야 합니다.</a></td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  다음에 대한 원격 지침이 제공됩니다.
<ul>
<li>  Project Online이 사용하는 기본 SharePoint 기능 확인  </li>
<li>  테넌트에 Project Online 서비스 추가(사용자에게 구독 추가 포함)  </li>
<li>  ERP(Enterprise 자원 그룹) 설정  </li>
<li>  첫 번째 프로젝트 만들기  </li>
</ul></td>
<td>Project for Office 365와 같은 온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 및 Office의 시스템 요구 사항에 정의된 것처럼 최소 수준이 되어야 합니다.</a></td>
</tr>
<tr class="odd">
<td><strong>Project Online Professional 및 Premium</strong></td>
<td>  다음에 대한 원격 지침이 제공됩니다.
<ul>
<li>  배포 문제 해결  </li>
<li>  Microsoft 365 관리 센터 및 Windows PowerShell을 사용하여 최종 사용자 라이선스 할당  </li>
<li>  간편 실행을 사용하여 Office 365 포털에서 Project Online 데스크톱 클라이언트 설치  </li>
<li>  Office 365 배포 도구를 사용하여 업데이트 설정 구성  </li>
<li>  Project Online 데스크톱 클라이언트를 위한 단일 사이트에 배포 서버 설정(Office 365 배포 도구용 configuration.xml 파일을 만드는 지침 포함)  </li>
<li>  Project Online 데스크톱 클라이언트을 Project Online Professional 또는 Project Online Premium에 연결합니다.  </li>
</ul></td>
<td>Project for Office 365와 같은 온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 및 Office의 시스템 요구 사항에 정의된 것처럼 최소 수준이 되어야 합니다.</a></td>
</tr>
<tr class="even">
<td><strong>SharePoint Online 및 비즈니스용 OneDrive</strong></td>
<td>  다음에 대한 원격 지침이 제공됩니다.
<ul>
<li>  DNS 설정.  </li>
<li>  방화벽 포트 구성  </li>
<li>  사용자 및 라이선스 프로비전  </li>
<li>SharePoint Online 관리자에 대해 사이트 만들기를 사용하도록 설정</li>
<li>사이트 모음 계획</li>
<li>콘텐츠 보호 및 권한 관리</li>
<li>SharePoint Online 기능 구성</li>
<li>  하이브리드 검색, 하이브리드 사이트, 하이브리드 분류, 콘텐츠 형식, 하이브리드 셀프 서비스 사이트 만들기(SharePoint Server 2013 전용), 확장된 앱 시작 관리자, 하이브리드 비즈니스용 OneDrive, 익스트라넷 사이트 등의 SharePoint 하이브리드 기능을 구성합니다.  </li>
<li>  마이그레이션에 대한 사용 방식  </li>
</ul>
다음과 같이 SharePoint 버전에 따라 비즈니스용 OneDrive에 대한 추가 지침이 제공됩니다.
<ul>
<li>  통합 옵션 식별 및 온-프레미스 및 온라인 네트워크 인프라와 대역폭 검토  </li>
<li>  SharePoint Online 2013 SP1(해당되는 경우), 동기화 및 ID 요구 사항을 계획 및 구현하고, 비즈니스용 OneDrive 동기화 클라이언트 식별  </li>
<li>  모든 사용자(또는 단계별 배포)에 대한 단일 롤아웃을 계획 및 구현합니다.  </li>
<li>  라이선스를 할당하고, 내 사이트 및 개인 문서 라이브러리를 Office 365로 리디렉션(SharePoint Online 2013에 해당)하여 대상 그룹을 설정하여 OneDrive에 대한 액세스를 제어합니다(SharePoint Online 2013에 해당됨).  </li>
<li>알려진 폴더를 OneDrive로 리디렉션 또는 이동</li>
<li>  비즈니스용 OneDrive 클라이언트 동기화 배포  </li>
</ul>
  <strong>데이터 마이그레이션</strong>  <br>
Office 365로의 데이터 마이그레이션에 대한 FastTrack 혜택을 사용하는 방법에 대한 자세한 내용은 데이터 <a href="https://review.docs.microsoft.com/fasttrack/data-migration">마이그레이션을 참조하세요.</a>
</ul></td>
<td><br><strong>SharePoint 하이브리드의 경우:</strong>  
<ul>
<li>  SharePoint 하이브리드 구성에는 온-프레미스에서 단일 대상 SharePoint Online 환경으로 연결된 하이브리드 검색, 사이트, 분류, 콘텐츠 형식, 비즈니스용 OneDrive, 확장된 앱 시작 관리자, 엑스트라넷 사이트 및 셀프 서비스 사이트 만들기 구성이 포함됩니다.  </li>
</ul>
  <strong>참고:</strong> 셀프 서비스 사이트 만들기는 SharePoint 2013을 실행하는 온-프레미스 서버에 포함되지 않습니다.  
<ul>
<li>  SharePoint 하이브리드를 사용하려면 다음 온-프레미스 SharePoint Server 환경 중 하나: 2013, 2016 또는 2019가 필요합니다.  </li>
</ul>
  <strong>참고:</strong> 온-프레미스 SharePoint 환경을 SharePoint Server로 업그레이드하는 것은 범위 내에 있지 않습니다. Microsoft <a href="https://go.microsoft.com/fwlink/?linkid=2080150">파트너에게</a> 도와문하십시오. 자세한 내용은 <a href="https://go.microsoft.com/fwlink/?linkid=853548">SharePoint 하이브리드 기능에 대한 최소 공개 업데이트 수준을 참조하세요.</a><em>.</em>  <br>
  <strong>참고:</strong> 다중 위치 기능에 대한 자세한 내용은 <a href="https://go.microsoft.com/fwlink/?linkid=831056">Office 365의 OneDrive 및 SharePoint Online의 다중 위치 기능을 참조하세요.</a><em>.</em>  </td>
</tr>
<tr class="odd">
<td><strong>비즈니스용 Skype Online</strong></td>
<td>  다음에 대한 원격 지침이 제공됩니다.
<ul>
<li>  방화벽 포트 구성  </li>

<li>  DNS 설정.  </li>
<li>  네트워크 평가:
<ul>
<li>  포트 및 끝점 검사  </li>
<li>  연결 품질 검사  </li>
<li>  대역폭 예상  </li>
</ul></li>
<li>  채팅방 시스템 장치용 계정 만들기  </li>
<li>  지원되는 비즈니스용 Skype 온라인 클라이언트 배포  </li>
<li>  온-프레미스 Lync 2010, Lync 2013 또는 비즈니스용 Skype 2015 서버 환경 및 비즈니스용 Skype 온라인 테넌트(해당하는 경우), 통화 계획, Skype 모임 브로드캐스트, 전화 시스템 및 통화 계획(사용 가능한 시장) 간에 분할 도메인 서버 구성을 설정합니다.  
  해당하는 경우 FastTrack은 다음을 안내합니다.  </li>
<li>  회의실 시스템 장치 구성:
<ul>
<li>  비즈니스용 Skype 솔루션 카탈로그의 회의실 시스템에 나열된 지원되는 회의실 장치에 <a href="https://go.microsoft.com/fwlink/?LinkId=615775">필요한 온라인 계정을 만듭니다.</a>  </li>
</ul></li>
<li>  하이브리드 및 분할된 도메인 서버 구성  </li>
<li>  오디오 회의 구성:
<ul>
<li>  회의 브리지 기본 설정에 대한 조직 설정  </li>
<li>  회의 브리지를 라이선스가 있는 사용자에게 할당  </li>
</ul></li>
<li>  전화 시스템 기본 설정 구성:
<ul>
<li>  통화 플랜:
<ul>
<li>  사용자에게 번호 할당  </li>
<li>  사용자 인터페이스를 통해 최대 99개까지의 지역 번호 이식 지침  </li>
<li>  999개가 초과하는 지역 번호 이식 서비스 요청 지원  </li>
</ul></li>
</ul></li>
<li>  비즈니스용 Skype 모임 브로드캐스트 구성:
<ul>
<li>  모임 브로드캐스트 서비스가 있는 페더레이션에 대한 조직 설정  </li>
</ul></li>
</ul></td>
<td>  <strong>Lync 하이브리드의 경우:</strong>  
<ul>
<li>  단일 온-프레미스 Active Directory 포리스트  </li>
<li>  Lync 2013 관리 도구 또는 비즈니스용 Skype 2015 관리 도구가 있는 Lync 2010 서버 환경 및 Lync 2010 에지 서버 역할  </li>
<li>  Lync 2013 서버 환경 및 Lync 2013 에지 서버 역할  </li>
</ul>
  <strong>비즈니스용 Skype 하이브리드:</strong>  
<ul>
<li>  단일 온-프레미스 Active Directory 포리스트  </li>
<li>  단일 Active Directory 계정 포리스트 이상 및 리소스 포리스트(Exchange 및/또는 비즈니스용 Skype) 토폴로지  </li>
<li>  Exchange 및/또는 비즈니스용 Skype에 중앙 집중식 Active Directory 계정 포리스트 하나가 포함된 여러 Active Directory 계정 포리스트  </li>
<li>  비즈니스용 Skype 에지 서버 역할을 포함하는 비즈니스용 Skype Server 2015 환경  </li>
</ul>
  <strong>참고:</strong> 이 추가 서비스는 분할 도메인(하이브리드) 작업의 구성 및 유효성 검사용이고, 온-프레미스 구성 요소(예: Lync 2013 관리 도구 또는 Lync 2013/비즈니스용 Skype 온라인 서버 또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype 에지 서버) 도입을 포함하지 않습니다.  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td><ul>
Microsoft에서는 엔터프라이즈 서비스를 사용하도록 설정하는 데 에디하며 Yammer 지침을 제공합니다.  
</ul></td>
<td>온라인 클라이언트 소프트웨어는 Microsoft 365 및 Office의 시스템 요구 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">사항에 정의된 적어도 수준으로 있어야 합니다.</a></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Enterprise Mobility & 보안

<table>
<thead>
</tr>
<tr class="even">
<td><strong>Azure AD(Azure Active Directory) 및 Azure AD Premium</strong></td>
<td>  다음 시나리오에 대한 클라우드 ID 보안을 위해 원격 지침을 제공합니다.  

 <br/>

<strong>Secure Foundation 인프라</strong>  </ul>
<ul>
<li>  Azure MFA(Multi-Factor Authentication)(클라우드 전용), Microsoft Authenticator 앱, Azure MFA 및 SSPR(셀프 서비스 암호 재설정)에 대한 결합을 포함하여 ID에 대한 강력한 인증 구성 및 사용.  </li>
<li>  Azure AD Premium이 아닌 고객의 경우 보안 기본값을 사용하여 ID를 보호하기 위한 지침이 제공됩니다.  </li>
<li>  Azure AD Premium 고객의 경우 조건부 액세스로 ID를 보호하기 위한 지침이 제공됩니다.  </li>
<li>  Azure AD 암호 보호에서 약한 암호의 사용을 감지하고 차단  </li>
<li>  Azure AD 응용 프로그램 프록시를 사용하여 온-프레미스 웹앱에 대한 원격 액세스 보안  </li>
<li>  Azure ID 보호를 사용하여 위험 기반 검색 및 업데이트 관리 사용  </li>
<li>  사용자 지정 브랜딩으로 로고, 텍스트 및 이미지를 포함한 사용자 지정된 로그인 화면을 사용하도록 설정  </li>
<li>  Azure AD B2B를 사용하여 게스트 사용자와 앱 및 서비스를 안전하게 공유합니다.  </li>
<li>  RBAC(역할 기반 액세스 제어) 기본 제공 관리 역할을 사용하여 Office 365 관리자의 액세스 권한을 관리하고 권한 있는 관리자 계정의 수를 줄입니다.  </li>
<li>  하이브리드 Azure AD 조인을 구성합니다.  </li>
<li>  Azure AD 조인을 구성합니다.  </li>
</ul>
  
<strong>모니터링 및 보고</strong>  
<ul>
<li>  
  Azure AD Connect Health로 AD FS, Azure AD Connect 및 도메인 컨트롤러에 대한 원격 모니터링을 사용하도록 설정  
  </li>
</ul>
  
<strong>거버넌스</strong>  
<ul>
<li>  
  Azure AD 권한 관리를 사용하여 Azure AD ID 및 액세스 수명 주기를 관리합니다.
  </li>
<li>  
  Azure AD 액세스 검토를 사용하여 Azure AD 그룹 구성원 자격, 엔터프라이즈 앱 액세스 및 역할 할당을 관리합니다.  
  </li>
<li>  
  Azure 의사용 약관 검토  
  </li>
<li>  
  Azure AD Privileged Identity Management를 사용하여 권한 있는 관리자 계정에 대한 액세스 관리 및 제어  
  </li>
</ul>
  
<strong>자동화 및 효율성 </strong>  
<ul>
<li>  
  Azure AD SSPR을 사용하도록 설정  
  </li>
<li>  Azure AD 셀프 서비스 그룹 관리를 통해 사용자가 자신의 클라우드 보안 또는 Office 365 그룹을 만들고 관리할 수 있도록 허용합니다.  </li>
<li>  Azure AD 위임 그룹 관리를 사용하여 엔터프라이즈 앱에 대한 위임된 액세스 관리  </li>
<li>  Azure AD 동적 그룹 사용  </li>
<li>  컬렉션을 사용하여 내 앱 포털에서 앱 구성  </li>
</ul></td>
<td>Azure AD 및 Azure AD Premium 기능과의 통합을 방지하는 식별된 문제를 수정하기 위해 온-프레미스 Active Directory와 해당 환경이 Azure AD Premium용으로 준비되었습니다.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection(P2 또는 EMS E5)</strong></td>
<td>  다음 작업 방법을 안내합니다.
<ul>
<li>  테넌트를 활성화하고 구성하기  </li>
<li>  레이블과 정책을 만들고 설정하기  </li>
<li>  문서에 정보 보호 적용하기  </li>
<li>  Azure Information Protection 클라이언트를 사용하여 Windows에서 실행 중인 Office 앱(Word, PowerPoint, Excel, Outlook 등)에서 자동으로 정보 분류 및 레이블 지정하기  </li>
<li>  Azure Information Protection 스캐너를 사용하여 보관 중인 파일 사용하기  </li>
<li>  Exchange Online 메일 흐름 규칙을 사용하여 전송 중인 전자 메일 모니터링하기  </li>
</ul>
Microsoft Azure RMS(권한 관리 서비스), OME(Office 365 메시지 암호화) 및 DLP(데이터 손실 방지)를 사용하여 보호를 적용하려는 경우 지침도 제공합니다.  </td>
<td>  다음과 같은 설정이 구성되어 있어야 합니다.
<ul>
<li>  Azure AD 사용.  </li>
<li>  Windows 또는 iOS(다른 운영 체제는 다되지 않음) 사용  
  </ul>
<strong>참고:</strong>컴퓨터 및 모바일 디바이스는 Azure Information <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">Protection을 지원하는 운영</a> 체제에서 실행해야 합니다.  
<li>  주 파일 공유 위치 보세요.  </li>
<strong>참고</strong>: 하이브리드 지원을 사용하려면 AD RMS 커넥터가 필요합니다. 
<li>  승인된 분류체계 보수  </li>
<li>  보호되는 키 관리에 대한 어법 제한사항을 이해합니다.  </li>
</ul>
  
<strong>Azure Information Protection 스캐너</strong>  
  
다음과 같은 설정이 구성되어 있어야 합니다.  
<ul>
<li>  설치 관리자 Windows Server 2012 R2 또는 Windows Server 2016을 사용합니다.  </li>
<li>  인터넷 연결  </li>
<li>  로컬 Microsoft SQL Server 원격 인스턴스에서 2012 이상을 배포해야 합니다.  </li>
<li>  온-프레미스 Active Directory에 대해 만들고 Azure AD와 동기화하는 서비스 계정을 만듭니다.  </li>
<li>  다운로드한 AzInfoProtection.exe.  </li>
<li>  자동 분류/보호에 대한 레이블을 구성합니다.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  앱 및 장치용 클라우드 기반 MDM(모바일 장치 관리) 및 MAM(모바일 앱 관리) 공급자로 Intune을 사용하기 위한 준비에 대한 지침을 제공합니다. 정확한 단계는 원본 환경에 따라 다르며 모바일 장치와 모바일 앱 관리 요구 사항에 기반합니다. 해당 단계는 다음과 같습니다.
<ul>
<li>  최종 사용자에게 라이선스 부여  </li>
<li>  온-프레미스 Active Directory 또는 클라우드 ID(Azure AD)를 이용하여 Intune에서 사용할 ID 구성  </li>
<li>  Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기  </li>
<li>  다음과 같은 관리 요구 사항에 따라 MDM 기관 구성
<ul>
<li>  Intune이 유일한 MDM 솔루션인 경우 Intune을 MDM 기관으로 설정  </li>
</ul></li>
<li>  MDM 지침 제공:
<ul>
<li>  MDM 관리 정책의 유효성을 검사하는 데 사용할 테스트 그룹 구성  </li>
<li>  다음과 같은 MDM 관리 정책 및 서비스 구성
<ul>
<li>  웹 링크 또는 전체 링크를 통해 지원되는 각 플랫폼용 앱 배포  </li>
<li>  조건부 액세스 정책.  </li>
<li>  조직에서 기존 인증 기관, 무선 네트워크 또는 VPN 인프라를 보유하고 있는 경우 전자 메일, 무선 네트워크, VPN) 프로필 배포  </li>
<li>  Microsoft Intune Exchange Connector 설정(해당하는 경우)  </li>
<li>  Intune 데이터 웨어하우스에 연결  </li>
<li>  다음에 Intune 통합:
<ul>
<li>  원격 지원을 위한 팀 뷰어(팀 뷰어 구독 필수)  </li>
<li>  MTD(Mobile Threat Defense) 파트너 솔루션(MTD 구독 필수)  </li>
<li>  Telecom Expense Management 솔루션(Telecom Expense Management 구독 필수)  </li>
<li>  Microsoft Defender ATP(Windows E5 또는 Microsoft 365 E5 라이선스 필요)  </li>
</ul></li>
<li>  각 지원되는 플랫폼의 장치를 Intune에 등록합니다.  </li>
</ul></li>
</ul></li>
<li>  앱 보호 지침 제공:
<ul>
<li>  지원되는 각 플랫폼에 대한 Intune 앱 보호 정책 구성  </li>
<li>  관리되는 앱에 대한 조건부 액세스 정책 구성  </li>
<li>  이전에 언급한 MAM 정책을 사용하여 적절한 사용자 그룹을 대상으로 지정  </li>
<li>  관리 앱 사용 현황 보고서 사용  </li>
</ul></li>
<li>  레거시 PC 관리에서 Intune MDM에 마이그레이션 지침 제공  </li>
</ul>
  <strong>참고</strong>: 2020년 10월 15일 이후로부터 는 레거시 PC 관리가 더 이상 지원되지 않습니다.  
</li>
</ul>
  
<strong>클라우드 연결</strong>  

  Intune을 사용하여 기존의 Configuration Manager 환경을 클라우드 연결하기 위한 준비를 안내합니다. 정확한 단계는 원본 환경에 따라 다릅니다. 해당 단계는 다음과 같습니다.  
<ul>
<li>  Intune을 사용하여 클라우드에 연결하는 방법에 대해 설명합니다.  </li>
<li>  최종 사용자에게 라이선스 부여  </li>
<li>  온-프레미스 Active Directory 및 클라우드 ID를 활용하여 Intune에서 사용할 ID 구성  </li>
<li>  Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기  </li>
<li>  Configuration Manager 콘솔에서 클라우드 연결을 사용하도록 설정합니다.  </li>
<li>  하이브리드 Azure AD 조인설정에 대한 지침을 제공합니다.  </li>
<li>  MDM 자동 등록을 위해 Azure AD 설정하는 것에 대한 지침을 제공합니다.  </li>
<li>  클라우드 관리 게이트웨이를 설정하는 방법에 대한 지침을 제공합니다.  </li>
<li>  Intune으로 전환할 지원되는 작업 부하를 구성합니다.  </li>
<li>  Intune에서 등록된 디바이스에서 Configuration Manager 클라이언트를 설치합니다.  </li>
</ul> 

<strong>iOS 및 Android용 Outlook 모바일을 안전하게 배포</strong> 사용자가 필요한 모든 앱을 설치하도록 조직에서 iOS 및 Android용 Outlook 모바일을 안전하게 배포하는 데 도움이 되는 지침을 제공할 수 있습니다.  
  Intune을 사용하여 iOS 및 Android용 Outlook 모바일을 안전하게 배포하는 단계는 원본 환경에 따라 다릅니다. 다음과 같이 사용할 수 있습니다.
<ul>
<li>  Apple App Store 또는 Google Play 스토어를 통해 iOS 및 Android용 Outlook, Microsoft Authenticator 및 Intune Company Portal 앱 다운로드  </li>
<li>  설정에 대한 지침 제공:
<ul>
<li>  Intune을 사용한 iOS 및 Android용 Outlook, Microsoft Authenticator 및 Intune Company Portal 앱 배포  </li>
<li>  앱 보호 정책.  </li>
<li>  조건부 액세스 정책.  </li>
<li>  앱 구성 정책.  </li>
</ul></li>
</ul>
  
  <strong>참고:</strong>FastTrack은 Exchange 모바일 장치 사서함 정책을 사용하여 iOS 및 Android용 Outlook 보안을 지원하지 않습니다. 이에 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">대한 지원을</a> 받기만 하면 Microsoft 파트너에 문의하세요.  
  </td>
<td>  IT 관리자는 Intune에서 무선 네트워크 및 VPN 프로필 배포를 계획할 때 기존 인증 기관, 무선 네트워크 및 VPN 인프라를 프로덕션 환경에서 이미 사용하고 있어야 합니다.  
  <strong>참고:</strong>Intune에 대한 인증 기관, 무선 네트워크, VPN 인프라 또는 Apple MDM 푸시 인증서를 설정 또는 구성하기 위한 지원은 FastTrack 서비스 혜택에 포함되지 않습니다.  

<strong>Intune을 사용하여 Configuration Manager를 클라우드에 연결</strong>  

 클라우드 연결 기능을 사용하여 IT 관리자는 온-프레미스 환경을 준비해야 합니다. 여기에는 Configuration Manager 환경을 Intune과 클라우드에 연결하지 못하도록 방지하는 문제의 수정이 포함될 수 있습니다.  
  <strong>참고</strong>: 클라우드 연결 기능을 지원하는 데 필요한 최소 요구 사항에 맞게 Configuration Manager 사이트 서버 또는 Configuration Manager 클라이언트를 설정하거나 업그레이드하기 위한 지원은 FastTrack 서비스 혜택에 포함되지 않습니다. 이에 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">대한 지원을</a> 받기만 하면 Microsoft 파트너에 문의하세요.

  <strong>Microsoft Defender ATP(Advanced Threat Protection)에 통합된 Intune</strong> 
 
  <strong>참고:</strong>Intune과 Microsoft Defender ATP를 통합하고 Windows 10 위험 수준 평가에 따라 장치 준수 정책을 만들기 위한 지원을 제공합니다. 구입, 라이선스 또는 정품 인증에 대한 지원은 제공하지 않습니다. 이에 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">대한 지원을</a> 받기만 하면 Microsoft 파트너에 문의하세요.  
  
<strong>Windows Autopilot</strong> 
 
  IT 관리자는 하드웨어 공급 업체가 사용자를 대신하여 하드웨어 ID를 업로드하거나 Windows Autopilot 서비스로 업로드하는 방법으로 조직에 장치를 등록합니다.  
  
<strong>Intune을 사용하여 iOS 및 Android용 Outlook을 안전하게 배포 </strong>  
<ul>
<li>  Office 365용 Azure AD에서 사용자 ID사용.  </li>
<li>  사용자 라이선스를 할당하여 구성된 Exchange Online 또는 하이브리드 Exchange  </li>
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
<th><strong>원본 환경 기대</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  Windows 7 Professional 및 Windows 8.1 Professional에서 Windows 10 Enterprise로 업그레이드하는 데 도움이 되는 지침을 제공합니다.  
  다음에 대한 원격 지침이 제공됩니다.
<ul>
<li>  Windows 10 의도 이해  </li>
<li>  원본 환경 및 요구 사항 평가(Microsoft Endpoint Configuration Manager가 Windows 10 배포를 지원하는 데 필요한 수준으로 업그레이드되는지 확인)  </li>
<li>  Microsoft Endpoint Configuration Manager 또는 Microsoft 365를 사용하여 Windows 10 Enterprise 및 Microsoft 365 앱을 배포합니다.  </li>
<li>  Windows 10 앱을 평가하는 데 권장 옵션이 있습니다.  </li>
<li>  Desktop Analytics 배포 계획 만들기를 통해 Desktop Analytics 및 지침 사용  </li>
<li>  Configuration Manager에서 Office 365 준비 상태 대시보드를 사용하거나 Office에 Office 365 앱을 배포하는 데 도움을 주기 위한 독립형 준비 Toolkit 사용하여 Microsoft 365 앱 호환성 평가.  </li>
<li>  Microsoft Intune을 사용하여 클라우드 연결 구성 관리자를 포함 또는 단독 클라우드 관리 솔루션으로서 Intune을 배포하는 등의 최신 관리 전략을 평가합니다.  </li>
<li>  원본 환경을 성공적인 배포에 필요한 최소 요구 사항에 따라 수행할 작업에 대한 재구성 검사 목록을 만듭니다.  </li>
<li>  기존 장치가 필요한 장치 하드웨어 요구 사항을 충족하는 경우 기존 장치를 Windows 10 Enterprise에 대한 업그레이드 지침을 제공합니다.  </li>
<li>  기존 배포 동작을 지원하기 위한 업그레이드 지침 제공 FastTrack은 Windows 10으로의 준비된 업그레이드를 위한 지침을 권장하고 제공합니다. Windows 정리 이미지 설치 및 Windows Autopilot 배포 시나리오에서도 지침을 사용할 수 있습니다.  </li>
<li>  Windows 10 배포의 일부로 Configuration Manager를 사용하여 Microsoft 365 앱을 배포.   </li>
<li>  조직에서 기존 Configuration Manager 환경 또는 Microsoft 365를 사용하여 Windows 10 Enterprise 및 Microsoft 365 앱을 최신 상태로 유지할 수 있는 지침을 제공합니다.  </li>
<li>  클라우드 구성 관리자를 Intune에 설치하거나 Intune 독립 실행형(필수)을 배포하여 최신 관리를 활성화하는 지침을 제공합니다.  </li>
</ul>
  <strong>다음 범위를 벗어나는 경우 </strong>  
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
이러한 서비스에 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">대한 지원을</a> 받기 만드리고 Microsoft 파트너에게 문의하세요.  </td>
<td>  PC 업그레이드의 경우, 다음 요구 사항을 충족해야 합니다.
<ul>
<li>  원본 OS: Windows 7 Enterprise 또는 Professional, Windows 8.1 Enterprise 또는 Professional  </li>
<li>  장치: 데스크톱, 노트북 또는 태블릿 폼 팩터  </li>
<li>  대상 OS: Window 10 Enterprise.  </li>
</ul>
인프라 업그레이드의 경우, 다음 요구 사항을 충족해야 합니다.
<ul>
<li>  Microsoft Endpoint Configuration Manager.  </li>
<li>  Configuration Manager 버전은 Windows 10 대상 버전에서 지원해야 합니다. 자세한 내용은 Configuration Manager에서 Windows 10 지원 시 Configuration <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Manager 지원 테이블을 참조하세요.</a>  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP)는 엔터프라이즈 네트워크가 고급 위협을 방지, 탐지, 조사 및 대응하는 데 도움이 되도록 설계된 플랫폼입니다.  
  다음에 대한 원격 지침이 제공됩니다.
<ul>
<li>  끝점을 안전하게 보호하기 위한 기술 배포  </li>
<li>  엔드포인트 보호 및 장치 제한 프로필 구성  </li>
<li>  OS 버전 및 장치 관리(Intune, Microsoft Endpoint Configuration Manager, GPO(그룹 정책 개체) 및 타사 구성 포함)과 Windows Defender AV 서비스 또는 기타 끝점 보안 소프트웨어의 상태를 평가하는 작업  </li>
<li>  Windows AV 서비스 또는 기타 엔드포인트 보안 소프트웨어의 상태 평가.  </li>
<li>  네트워크 트래픽을 제한하는 프록시 및 방화벽 평가.  </li>
<li>  온보드 엔드포인트를 사용하여 ATP 에이전트 프로필을 배포하는 방법을 설명하여 Microsoft Defender ATP 서비스를 사용하도록 설정  </li>
<li>  배포 지침, 구성 지원 및 교육:
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
<li>  시뮬레이션 및 자습서(연습 시나리오, 가까운 맬웨어 및 자동화된 조사) 검토  </li>
<li>  보고 및 위협 분석 기능에 대한 개요입니다.  </li>
<li>  Office 365 ATP와 Microsoft Defender ATP 통합.  </li>
<li>  Microsoft Defender 보안 센터 포털 탐색.  </li>
<li>  다음 운영 체제
<ul>
<li>  
  Windows 10.  
  </li>
<li>  
  Windows Server 2016.  
  </li>
<li>  
  Windows Server 2019.  
  </li>
<li>  
  Windows Server 2019 Core Edition.  
  </li>
<li>  
  Windows Server SAC(반기 채널) 버전 1803.  
  </li>
<li>  
  macOS 버전 10.13, 10.14 및 10.15.  
  </li>
</ul>
</li>
</ul>
<strong>참고:</strong> 모든 Windows Server 버전은 최신 버전의 System Center Configuration Manager 2012(버전 1012 R2, 1511 또는 1602)나 Microsoft Endpoint Configuration Manager(버전 2002 이상)를 통해 관리해야 합니다. 

</li>
</ul>

<strong>다음 범위를 벗어나는 경우 </strong>  
<ul>
<li>  고객의 수정 활동에 대한 프로젝트 관리.  </li>
<li>  현장 지원.  </li>
<li>  지속적인 관리와 위협 대응.  </li>
<li>  다음 Microsoft Defender ATP 에이전트에 대한 온보딩 또는 구성:
<ul>
<li>  
  Windows Server 2008.  
  </li>
<li>  
  Windows Server 2012.  
  </li>
<li>  
  Linux.  
  </li>
<li>  
  모바일 장치(Android 및 iOS).  
  </li>
</ul></li>
<li>  서버 온보딩 및 구성:
<ul>
<li>  
  오프라인 통신을 위한 프록시 서버 구성  
  </li>
<li>  
  하위 수준의 Configuration Manager 인스턴스 및 버전에서 Configuration Manager 배포 패키지 구성  
  </li>
<li>  
  Azure Security Center에 서버 온보딩  
  </li>
<li>  
  구성 관리자를 사용하여 관리하지 않는 서버.  
  </li>
</ul></li>
<li>  macOS 온보딩 및 구성:
<ul>
<li>  
  수동 Intune 기반 배포.  
  </li>
<li>  
  JAMF 기반 배포.
  </li>
<li>  
  기타 MDM(모바일 장치 관리) 제품 기반 배포.  
  </li>
<li>  
  수동 배포.  
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
<li>  API 또는 SIEM(보안 정보 및 이벤트 관리) 연결 검토 나는 구성 또는 교육  </li>
<li>  MTP(Microsoft 위협 방지) 등록 또는 구성.  </li>
<li>  고급 헌팅에 대한 교육 또는 지침.  </li>
<li>  Kusto 쿼리의 사용 또는 만들기를 다루는 교육 또는 지침</li>
</li>
</ul>
이러한 서비스에 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">대한 지원을</a> 받기 만드리고 Microsoft 파트너에게 문의하세요.  
</ul></td>
<td></td>

</tbody>
</table>
