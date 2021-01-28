---
title: 제품 및 기능
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/27/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: 이 항목에는 FastTrack에서 지원하는 작업 시나리오와 시작하기 전에 필요한 원본 환경 기대치에 대한 세부 정보가 포함되어 있습니다. 현재 설정에 따라 성공적인 온보드를 위한 최소 요구 사항까지 원본 환경을 개선하는 재구성 계획을 세우기 위해 함께 작업합니다.
ms.openlocfilehash: abbc97a7b2d70b0b0111f1cbe96904bbe552e463
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016690"
---
# <a name="products-and-capabilities"></a>제품 및 기능

## <a name="services-and-scenarios-supported-by-fasttrack"></a>FastTrack에서 지원하는 서비스 및 시나리오

이 항목에는 FastTrack에서 지원하는 작업 시나리오와 시작하기 전에 필요한 원본 환경 기대치에 대한 세부 정보가 포함되어 있습니다. 현재 설정에 따라 성공적인 온보드를 위한 최소 요구 사항까지 원본 환경을 개선하는 재구성 계획을 세우기 위해 함께 작업합니다.

FastTrack은 먼저 핵심 기능(모든 사용자에 대해 공통)을 제공한 다음 적합한 각 서비스를 온보더링하는 데 도움이 Microsoft Online Services 되는 지침을 제공합니다.

  - [일반](#general)
  - [보안 및 규정 준수](#security-and-compliance)
  - [Office 365](#office-365)
  - [Enterprise Mobility + Security](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [Windows Virtual Desktop](#windows-virtual-desktop)
  - [App Assure](#app-assure)
  - [Microsoft Edge](#microsoft-edge)

> [!NOTE]
> Office 365 미국 정부에 대한 원본 환경 기대치에 대한 정보는 [Office 365 미국 정부에 대한 원본 환경 기대치](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)를 참조하세요. 
 
## <a name="general"></a>일반 사항

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
<td>  서비스 프로비전, 테넌트 및 ID 통합과 관련된 핵심 온보드에 대한 원격 지침을 제공합니다. 또한 보안, 네트워크 연결 및 규정 준수에 대한 토론을 포함하여 Exchange Online, SharePoint Online 및 Microsoft Teams와 같은 온보더링 서비스에 대한 기초를 제공하기 위한 단계도 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">포함되어 있습니다.</a>  
  하나 이상의 적합한 서비스에 대한 온보딩은 핵심 온보딩이 완료되면 시작됩니다.
</li>
</ul>  

<strong> ID 통합 </strong>

다음에 대한 원격 지침을 제공합니다.
<ul>
<li>Azure AD Connect(단일 포리스트 또는 다중 포리스트) 및 라이선스(그룹 기반 라이선싱 포함)를 설치 및 구성하는 작업을 포함하여 Azure AD(Azure Active Directory)에 동기화하기 위한 On-premises Active Directory ID 준비</li>
<li>그룹 기반 라이선싱 사용을 포함하여 대량 가져오기 및 라이선스를 포함한 클라우드 ID 만들기</li>
<li>클라우드 여정, 암호 해시 동기화, 통과 인증 또는 AD FS(Active Directory Federation Services)에 대한 올바른 인증 방법을 선택하고 사용하도록 설정</li>
<li>Azure AD Connect 도구와 동기화된 단일 Active Directory 포리스트 및 ID를 사용하는 고객에 대해 AD FS를 사용하도록 설정 이렇게 하려면 Windows Server 2012 R2 Active Directory Federation Services 2.0 이상이 필요합니다.</li>
<li>암호 해시 동기화 또는 통과 인증을 사용하여 AD FS에서 Azure AD로 인증 마이그레이션</li>
<li>SSO(Single Sign-On)를 위해 사전 통합된 앱(예: Azure AD 갤러리 SaaS(Software-as-a-Service) 앱)을 AD FS에서 Azure AD로 마이그레이션합니다.</li>
<li>Azure AD 갤러리에서 SaaS 앱과 SSO를 통합할 수 있도록 설정</li>
<li>앱 통합 자습서 목록에 나열된 미리 통합된 SaaS 앱에 대해 자동 사용자 프로비전을 사용하도록 설정(Azure AD 갤러리 SaaS 앱 및 아웃바운드 프로비저닝으로 제한) <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list"></a>  </li>
</td>

<td>  <strong>네트워크 사용 설정 </strong>  
  <br>FastTrack 혜택의 일부로 Microsoft 365의 최고 수준의 성능을 보장하기 위해 클라우드 서비스에 연결하는 모범 사례를 활용하는 것이 좋습니다.  
  
<strong>Active Directory 포리스트</strong> 다음 포리스트 구성을 통해 포리스트 기능 수준이 Windows Server 2003 이상으로 설정됩니다.
<ul>
<li>  단일 Active Directory 포리스트.  </li>
<li>  단일 Active Directory 계정 포리스트 및 리소스 포리스트(Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype) 토폴로지  </li>
<li>  여러 개의 Active Directory 계정 포리스트 및 리소스 포리스트(Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype) 토폴로지  </li>
<li>  포리스트 중 하나가 Exchange 및/또는 Lync 2010, Lync 2013 또는 비즈니스용 Skype가 있는 중앙 집중식 Active Directory 계정 포리스트인 여러 Active Directory 계정 포리스트  </li>
<li>  각각이 자체 Exchange 조직을 갖는 다중 Active Directory 계정 포리스트  </li>
<li>  필요한 경우 테넌트 구성 및 Azure Active Directory와의 통합에 필요한 작업   </li>
</ul>
  <strong>중요</strong>  <ul>
<li>  다중 포리스트 Active Directory 시나리오의 경우 Lync 2010, Lync 2013 또는 비즈니스용 Skype가 배포된 경우 Exchange와 동일한 Active Directory 포리스트에 배포해야 합니다.  </li>
<li>  Exchange 다중 하이브리드 구성에서 여러 Exchange 조직과 함께 여러 Active Directory 포리스트를 구현하는 경우 원본 포리스트 간의 공유 UPN(사용자 계정 이름) 네임스페이스는 지원되지 않습니다. Exchange 조직 간의 기본 SMTP 네임스페이스도 구분해야 합니다. 자세한 내용은 여러 <a href="https://go.microsoft.com/fwlink/?linkid=845444">Active Directory 포리스트가 있는 하이브리드 배포를 참조하세요.</a>  </li>
<li>  모든 다중 포리스트 구성에서 AD FS(Active Directory Federation Services) 배포의 범위를 벗어날 수 있습니다. 이에 대한 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">지원은 Microsoft 파트너에게</a> 문의하세요.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft 365 앱</strong></td>
<td>  다음에 대한 원격 배포 지침을 제공합니다.
<ul>
<li>  배포 문제 해결  </li>
<li>  Microsoft 365 관리 센터 및 Windows PowerShell을 사용하여 최종 사용자 및 디바이스 기반 라이선스 할당  </li>
<li>  간편 실행을 사용하여 Office 365 포털에서 Microsoft 365 앱 설치  </li>
<li>  iOS 또는 Android 장치에 Office Mobile 앱(에: Outlook Mobile, Word Mobile, Excel Mobile 및 PowerPoint Mobile) 설치  </li>
<li>  Office 365 배포 도구를 사용하여 업데이트 설정 구성  </li>
<li>  로컬 또는 클라우드 설치의 선택 및 설치  </li>
<li>  배포 패티지를 구성하기 위해 Office 사용자 지정 도구 또는 네이티브 XML을 사용하여 Office 배포 도구 구성 XML 작성  </li>
<li>  Microsoft Endpoint Configuration Manager를 사용하여 배포(Endpoint Configuration Manager 패키지 생성에 대한 지원 포함)  
  또한 이전 버전의 Office와 함께 작동한 매크로나 추가 기능을 사용할 경우 호환성 문제가 있는 경우 App Assure 프로그램을 통해 추가 비용으로 호환성 문제를 해결하기 위한 지침을 제공합니다. 자세한 내용은 Windows <a href="#windows-10">10의</a> <strong>App Assure</strong> 부분을 참조하세요. </li>
</ul></td>
<td><ul>
<li>  온라인 클라이언트 소프트웨어는 Microsoft 365 및 Office의 시스템 요구 사항에 정의된 최소 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">수준 이상이 되어야 합니다.</a>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>네트워크 상태</strong></td>
<td>  Microsoft는 사용자 환경에서 조직의 사이트가 네트워크 연결의 Microsoft의 원칙에 얼마나 부합하는지 보여주는 주요 네트워크 연결 데이터를 획득하고 해석하는 원격 지침을 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">제공합니다.</a> 그러면 마이그레이션 속도, 사용자 환경, 서비스 성능 및 안정성에 직접적인 영향을 미치는 네트워크 점수가 강조 표시됩니다.  
  또한 네트워크 점수를 개선하는 데 도움이 될 수 있도록 이 데이터로 강조 표시된 모든 수정 단계를 안내합니다.  </td>
<td><ul>
<li>  Microsoft 365 관리 센터 액세스.  </li>
<li>  최신 버전의 Microsoft 365 앱이 필요합니다.  </li>
<li>  <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365</a>관리 센터(미리 보기)의 네트워크 성능 권장 사항에 따라 사용하도록 설정된 위치 서비스  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a>보안 및 규정 준수

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

<td><strong>Azure AD(Azure Active Directory) 및 Azure AD Premium</strong></td>
<td>  다음 시나리오에서 클라우드 ID를 보호하는 데 필요한 원격 지침을 제공합니다.  

 <br/>

<strong>보안 기본 인프라</strong>  </ul>
<ul>
<li>  Azure MFA(Multi-Factor Authentication)(클라우드 전용), Microsoft Authenticator 앱 및 Azure MFA 및 SSPR(셀프 서비스 암호 재설정)에 대한 결합 등록을 포함하여 ID에 대해 강력한 인증을 구성하고 사용하도록 설정  </li>
<li>  Azure AD Premium이 아닌 고객의 경우 보안 기본값을 사용하여 ID를 보호할 수 있는 지침이 제공됩니다.  </li>
<li>  Azure AD 프리미엄 고객의 경우 조건부 액세스로 ID를 보호할 수 있는 지침이 제공됩니다.  </li>
<li>  Azure AD 암호 보호를 사용하여 취약한 암호의 사용을 감지하고 차단합니다.  </li>
<li>  Azure AD 응용 프로그램 프록시를 사용하여 프레미스 웹앱에 대한 원격 액세스 보안  </li>
<li>  Azure ID 보호를 사용하여 위험 기반 검색 및 수정을 사용하도록 설정  </li>
<li>  사용자 지정 브랜드가 있는 로고, 텍스트 및 이미지를 포함하여 사용자 지정 로그인 화면 사용  </li>
<li>  Azure AD B2B를 사용하여 게스트 사용자와 앱 및 서비스를 안전하게 공유합니다.  </li>
<li>  RBAC(역할 기반 액세스 제어) 기본 제공 관리 역할을 사용하여 Office 365 관리자에 대한 액세스를 관리하고 권한 있는 관리자 계정 수를 줄입니다.  </li>
<li>  하이브리드 Azure AD 조인 구성  </li>
<li>  Azure AD 가입 구성  </li>
</ul>
  
<strong>모니터링 및 보고</strong>  
<ul>
<li>  
  Azure AD Connect Health를 사용하여 AD FS, Azure AD Connect 및 도메인 컨트롤러에 대한 원격 모니터링을 사용하도록 설정  
  </li>
</ul>
  
<strong>거버넌스</strong>  
<ul>
<li>  
  Azure AD 권리 부여 관리를 사용하여 Azure AD ID 및 액세스 수명 주기를 대규모로 관리합니다.
  </li>
<li>  
  Azure AD 액세스 검토를 사용하여 Azure AD 그룹 구성원 자격, 엔터프라이즈 앱 액세스 및 역할 할당 관리  
  </li>
<li>  
  Azure AD 사용 약관 검토  
  </li>
<li>  
  Azure AD Privileged Identity Management를 사용하여 권한 있는 관리자 계정에 대한 액세스를 관리하고 제어합니다.  
  </li>
</ul>
  
<strong>자동화 및 효율성 </strong>  
<ul>
<li>  
  Azure AD SSPR 사용  
  </li>
<li>  사용자가 Azure AD 셀프 서비스 그룹 관리를 사용하여 자체 클라우드 보안 또는 Office 365 그룹을 만들고 관리할 수 있도록 허용  </li>
<li>  Azure AD 위임된 그룹 관리를 사용하여 엔터프라이즈 앱에 대한 위임된 액세스 관리  </li>
<li>  Azure AD 동적 그룹을 사용하도록 설정  </li>
<li>  컬렉션을 사용하여 내 앱 포털에서 앱 구성  </li>
</ul></td>
<td>Azure AD 및 Azure AD Premium 기능과의 통합을 방지하는 식별된 문제의 수정을 포함하여 Azure AD Premium에 대한 On-premises Active Directory 및 해당 환경이 준비되었습니다.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection </strong></td>
<td>  다음에 대한 원격 지침을 제공합니다.
<ul>
<li>  테넌트 활성화 및 구성  </li>
<li>  레이블과 정책 만들기 및 설정  </li>
<li>  문서에 정보 보호 적용  </li>
<li>  Azure Information Protection 클라이언트를 사용하여 Windows에서 실행 중인 Office 앱(Word, PowerPoint, Excel, Outlook 등)에서 자동으로 정보 분류 및 레이블 지정  </li>
<li>  Azure Information Protection 스캐너를 사용하여 미사용 파일 검색 및 레이블 지정  </li>
<li>  Exchange Online 메일 흐름 규칙을 사용하여 전송 중인 전자 메일 모니터링  </li>
</ul>
Microsoft Azure RMS(권한 관리 서비스), OME(Office 365 메시지 암호화) 및 DLP(데이터 손실 방지)를 사용하여 보호를 적용하려는 경우도 지침을 제공합니다.  </td>
<td>  고객 선행 요구 사항 책임은 다음과 같습니다.
<ul>
<li>  검사할 파일 공유 위치 목록입니다.  </li>
<li>  승인된 분류 분류입니다. </li>
<li> 키 관리에 대한 규정 제한 또는 요구 사항을 이해합니다.  </li>
<li>  Azure AD와 동기화된,프레미스 Active Directory에 대해 만들어진 서비스 계정입니다. </li>
<li>  분류 및 보호를 위해 구성된 레이블입니다. </li>
<li> Azure Information Protection 스캐너에 대한 모든 선행이 준비됩니다. 자세한 내용은 Azure Information Protection 통합 레이블 지정 스캐너를 설치 및 배포하기 위한 선행 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">구성을 참조하세요.</a> </li>
<li>  사용자 장치가 지원되는 운영 체제를 실행하고 있으며 필수 필수가 설치되어 있는지 확인합니다. 자세한 내용은 다음을 참조합니다.</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">관리자 가이드: 사용자를 위한 Azure Information Protection 통합 레이블 지정 클라이언트 설치</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">iOS 또는 Android용 Azure Information Protection 앱은 무엇입니까?</a>  </li>
</ul>
<li> 하이브리드 지원을 위한 AD RMS(Active Directory RMS) 커넥터를 포함하여 Azure RMS 커넥터 및 서버의 설치 및 구성  </li>
<li> 배포에 이러한 옵션 중 하나를 필요로 하는 경우 BYOK(Bring Your Own Key), DKE(이중 키 암호화)(통합 레이블 지정 클라이언트만 해당) 또는 HYOK(Own Key)를 설치 및 구성합니다.  </li>
  </ul>
</ul>
  
</td>
</tr>

<tr class="even">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender는 엔드포인트, ID, 전자 메일 및 앱에 대한 감지, 방지, 조사 및 대응을 기본적으로 조정하여 정교한 공격으로부터 통합된 보호를 제공하는 통합 사전 및 사후 위반 엔터프라이즈 방어 제품군입니다. 다음에 대한 원격 지침을 제공합니다. </p> 
<ul>
<li>  Microsoft 365 보안 센터의 개요를 제공합니다.  </li>
<li>  전체 공격 범위, 영향을 미치는 자산 및 함께 그룹화되는 자동화된 수정 작업을 보장하여 중요한 작업에 중점을 두는 것을 포함하여 제품 간 인시던트 검토  </li>
<li>  Microsoft 365 Defender가 자동 자동 복구를 통해 손상될 수 있는 자산, 사용자, 장치 및 사서함에 대한 조사를 오케스트레이션하는 방법을 시연합니다. </li>
<li>  고객이 여러 데이터 집합에서 전자 메일, 데이터, 장치 및 계정에 영향을 주는 침입 시도 및 위반 활동을 사전 예방적으로 헌팅하는 방법을 설명하고 예제를 제공합니다.   </li>
<li> 고객에게 Microsoft 보안 점수를 사용하여 전체적으로 보안 자세를 검토하고 개선할 수 있는 방법을 보여 넣습니다.</li>
</ul>
<p><strong>다음은 범위를 벗어나는 예제입니다.</strong></p>
<ul>
<li> 고객의 수정 활동에 대한 프로젝트 관리. </li>
<li> 지속적인 관리, 위협 대응 및 수정. </li>
<li> 배포 지침 또는 교육:
<ul>
<li> 다양한 경고 유형 및 모니터링된 활동을 수정하거나 해석하는 방법 </li>
<li> 사용자, 컴퓨터, 측면 이동 경로 또는 엔터티를 조사하는 방법 </li>
<li> 사용자 지정 위협 헌팅.  </li>
</ul>
</li>
<li> SIEM(보안 정보 및 이벤트 관리) 또는 API 통합</li>
</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security는 모든 Microsoft 및 타사 클라우드 서비스에서 사이버 위협을 식별하고 퇴치하기 위한 풍부한 가시성, 데이터 이동 제어 및 정교한 분석을 제공하는 CASB(Cloud Access Security Broker)입니다. 다음에 대한 원격 지침을 제공합니다.
<ul>
<li>  다음을 포함하여 포털 구성  </li>
<ul>
<li> 사용자 그룹 가져오기.</li>
<li> 관리자 액세스 및 설정 관리  </li>
<li> 배포를 구성하여 모니터링하거나 모니터링에서 제외할 특정 사용자 그룹을 선택합니다.</li>
<li> IP 범위 및 태그 설정</li>
<li> 로고 및 사용자 지정 메시징을 사용하여 최종 사용자 환경을 개인 설정</li>
</ul>
<li> 클라우드 검색을 설정하여 섀도 IT를 제공합니다.</li>
<ul>
<li> 끝점용 Microsoft Defender.</li>
<li> Zscaler.</li>
<li> iboss.</li>
</ul>
<li> 앱 <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">커넥터를 사용하여</a> 주요 앱을 연결합니다.</li>
<li> 조건부 액세스 및 Cloud App Security 포털에서 조건부 액세스 앱 컨트롤을 설정하여 실시간 세션 컨트롤을 적용합니다.</li>
<li> Cloud App Security 및 클라우드 검색 대시보드 배포</li>
<li> 조직의 우선 순위에 따라 앱 위험 점수를 사용자 지정합니다.</li>
<li> 앱 태그 및 범주 만들기</li>
<li> 앱에 대한 인가 및 비이용성.</li>
<li> 활동 및 파일 로그 사용</li>
<li> OAuth 앱 관리</li>
<li> Microsoft 365 Defender 포털의 인시던트 상관 관계 이해</li>
<li> CASB의 상위 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20개</a> 사용 사례(다음을 제외한 최대 6개의 정책 생성 또는 업데이트 포함)에 대한 구성 지원을 제공합니다. </li>
<ul>
<li> IaaS(인터넷 as a Service) 환경의 구성 감사(#18.</li>
<li> IaaS 환경에서 위협으로부터 보호하기 위한 사용자 활동 모니터링(#19.</li>
</ul>
</ul>
<p><strong>다음은 범위를 벗어나는 예제입니다.</strong></p>
<ul>
<li> 고객의 수정 활동에 대한 프로젝트 관리.</li>
<li> 지속적인 관리, 위협 대응 및 수정. </li>
<li> Docker 또는 로그 수집기를 사용하여 연속 보고서에 대한 자동 로그 업로드 인프라, 설치 또는 배포 설정 자세한 내용은 CASB에 대한 상위 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20개</a> 사용 사례를 참조합니다.</li>
<li> 클라우드 검색 스냅숏 보고서 만들기</li>
<li> 블록 스크립트를 사용하여 앱 사용을 차단합니다.</li>
<li> 사용자 지정 앱 연결.</li>
<li> 타사 ISP(ID 공급자) 및 DLP(데이터 손실 방지) 공급자와 통합</li>
<li> 고급 헌팅에 대한 교육 또는 지침.</li>
<li> Microsoft Power Automate 플레이북을 포함한 자동화된 조사 및 수정</li>
<li> SIEM(보안 정보 및 이벤트 관리) 또는 API 통합(Azure Sentinel 포함)</li>
<li> 개념 증명으로 Cloud App Discovery 배포</li>
</ul></td>
</tr>



<tr class="even">
<td><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP)는 엔터프라이즈 네트워크가 고급 위협을 방지, 탐지, 조사 및 대응하는 데 도움이 되도록 설계된 플랫폼입니다.  
  다음에 대한 원격 지침을 제공합니다.
<ul>
<li>  끝점을 보호하는 기술을 배포합니다.  </li>
<li>  끝점 보호 및 장치 제한 프로필 구성  </li>
<li>  OS 버전 및 장치 관리(Intune, Microsoft Endpoint Configuration Manager, GPOS(그룹 정책 개체) 및 타사 구성 포함) 및 Windows Defender AV 서비스 또는 기타 끝점 보안 소프트웨어의 상태를 평가합니다.  </li>
<li>  Windows AV 서비스 또는 기타 끝점 보안 소프트웨어의 상태 평가  </li>
<li>  네트워크 트래픽을 제한하는 Proxies 및 방화벽 평가  </li>
<li>  온보딩 끝점을 사용하여 ATP 에이전트 프로필을 배포하는 방법을 설명하여 Microsoft Defender ATP 서비스를 사용하도록 설정  </li>
<li>  다음에 대한 배포 지침, 구성 지원 및 교육:
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
<li>  시뮬레이션 및 자습서 검토(예: 연습 시나리오, 가짜 맬웨어 및 자동화된 조사).  </li>
<li>  보고 및 위협 분석 기능 개요  </li>
<li>  Office 365 ATP와 Microsoft Defender ATP 통합.  </li>
<li>  Microsoft Defender 보안 센터 포털 탐색.  </li>
<li>  다음 운영 체제는 다음과 같습니다.
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
  Windows Server 2019 Core Edition  
  </li>
<li>  
  Windows Server Semi-Annual 채널(SAC) 버전 1803.  
  </li>
<li>  
  macOS 버전 10.13, 10.14 및 10.15.  
  </li>
</ul>
</li>
</ul>
<strong>참고:</strong> 모든 Windows Server 버전은 최신 버전의 System Center Configuration Manager 2012(버전 1012 R2, 1511 또는 1602) 또는 Microsoft Endpoint Configuration Manager(버전 2002 이상)에서 관리해야 합니다. 

</li>
</ul>

<strong>다음은 범위를 벗어나는 예제입니다. </strong>  
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
<li>  서버 온보더링 및 구성:
<ul>
<li>  
  오프라인 통신을 위한 프록시 서버 구성  
  </li>
<li>  
  다운 수준 Configuration Manager 인스턴스 및 버전에서 Configuration Manager 배포 패키지 구성  
  </li>
<li>  
  Azure 보안 센터에 서버 온보더링  
  </li>
<li>  
  Configuration Manager에서 관리되지 않는 서버입니다.  
  </li>
</ul></li>
<li>  macOS 온보더링 및 구성:
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
  앱 컨트롤.  
  </li>
<li>  
  악용 방지.  
  </li>
<li>  
  네트워크 방화벽.  
  </li>
</ul></li>
<li>  Microsoft 위협 전문가 등록 또는 구성.  </li>
<li>  API 또는 SIEM(보안 정보 및 이벤트 관리) 연결을 검토하는 구성 또는 교육  </li>
<li>  MTP(Microsoft 위협 방지) 등록 또는 구성.  </li>
<li>  고급 헌팅에 대한 교육 또는 지침.  </li>
<li>  Kusto 쿼리의 사용 또는 생성에 대한 교육 또는 지침입니다.</li>
</li>
</ul>
Microsoft 파트너에게 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">이러한</a> 서비스에 대한 지원을 요청하세요.  
</ul></td>
<td></td>

<tr class="odd">
<td><strong>Microsoft Defender for Identity </strong></td>
<td>  ID용 Microsoft Defender는 온-프레미스 Active Directory 신호를 활용하여 조직에서 일어나는 고급 위협, ID 손상 및 악의적인 내부자 작업을 식별, 감지 및 조사하는 클라우드 기반 보안 솔루션입니다. 다음에 대한 원격 지침을 제공합니다.
<ul>
<li>   ID용 Defender 인스턴스 만들기 </li>
<li>   ID용 Defender를 Active Directory에 연결합니다. </li>
<li>   다음을 포함하여 도메인 컨트롤러에 ID용 Defender 센서를 배포하기 위한 환경의 준비 상태를 평가합니다.</li>   
<ul> 
<li>  자원 용량 계획을 위한 크기 조정 도구 실행 </li>
<li>  감사 도구를 실행하여 센서와 도메인 컨트롤러의 호환성을 평가합니다. </li>
</ul>
<li>  다음을 포함하여 도메인 컨트롤러에서 직접 네트워크 트래픽 및 Windows 이벤트를 캡처하고 구문 분석하기 위해 센서를 배포합니다. </li>
<ul> 
<li>  센서 패키지 다운로드. </li>
<li>  센서 구성 </li>
<li>  자동으로 도메인 컨트롤러에 센서를 설치합니다. </li>
<li>  다중 포리스트 환경에 센서 배포 </li>
</ul>
<li>  ID용 Defender를 Microsoft Cloud App Security와 통합합니다(Cloud App Security 라이선스가 필요하지 않습니다). </li>
<li>  다음에 대한 배포 지침, 구성 지원 및 교육을 제공합니다. </li>
<ul>
<li> "노이즈"를 줄이기 위해 환경을 조정합니다.  </li>
<li>  ID 보안 환경 평가 보고서 이해 </li>
<li>  사용자 조사 우선 순위 점수 및 사용자 조사 순위 보고서 이해 </li>
<li> 비활성 사용자 보고서 이해  </li>
<li> 손상된 계정에 대한 수정 옵션 제공  </li>
</ul>
<li>  ATA(Advanced Threat Analytics)에서 ID용 Defender로의 마이그레이션을 촉진합니다. </li>
</ul>
<p><strong>다음은 범위를 벗어나는 예제입니다.</strong></p>
<ul>

<li> 고객의 수정 활동에 대한 프로젝트 관리. </li>
<li> 지속적인 관리, 위협 대응 및 수정.  </li>
<li> 다음을 포함하여 ID용 Defender 센서 배포 </li>
<ul>
<li> 수동 용량 계획 </li>
<li> 독립 실행형 용량으로 센서 배포 </li>
<li> NIC(Network Interface Card) 팀 어댑터를 사용하여 센서 배포 </li>
<li> 타사 도구를 통해 센서 배포. </li>
<li> 웹 프록시 연결을 통해 ID용 Defender 클라우드 서비스에 연결합니다. </li>
</ul>
<li> 벌집 만들기 및 관리 </li>
<li> 배포 지침 또는 교육: </li>
<ul>
<li> 다양한 경고 유형 및 모니터링된 활동을 수정하거나 해석합니다.  </li>
<li> 사용자, 컴퓨터, 측면 이동 경로 또는 엔터티 조사. </li>
<li> 위협 또는 고급 헌팅. </li>
<li> 인시던트 대응. </li>
</ul>
<li> ID용 Defender에 대한 보안 경고 랩 자습서를 제공합니다. </li>
<li> ID에 대한 Defender가 지명된 센서를 통해 syslog 서버에 보안 알림을 보내 의심스러운 활동을 감지할 때 알림을 제공합니다.  </li>
<li> SAMR(보안 계정 관리자 원격) 프로토콜을 사용하여 쿼리를 수행하여 특정 컴퓨터의 로컬 관리자를 식별하도록 ID에 대한 Defender를 구성합니다. </li>
<li> VPN 연결의 정보를 사용자의 프로필 페이지에 추가하도록 VPN 솔루션을 구성합니다.  </li>
<li> SIEM(보안 정보 및 이벤트 관리) 또는 API 통합(Azure Sentinel 포함) </li>
<li> 개념 증명으로 ID 센서용 Defender 배포</li>
</ul></td>
<td><ul>
<li>  Active Directory가 배포되었습니다.  </li>
<li>  ID용 Defender 센서를 설치하려는 도메인 컨트롤러는 ID용 Defender 클라우드 서비스에 인터넷에 연결되어 있습니다.  </li>
<ul>
<li> ID 클라우드 서비스용 Defender와 통신하려면 방화벽 및 프록시가 열려 있어야 합니다(*.atp.azure.com 포트 443이 열려 있어야 합니다).</li>
</ul>
<li> 다음 중 하나에서 실행되는 도메인 컨트롤러:</li>
<ul>
<li> Windows Server 2008 R2 SP1.</li>
<li> Windows Server 2012.</li>
<li> Windows Server 2012 R2</li>
<li> Windows Server 2016.</li>
<li> Windows Server 2019 KB4487044(OS 빌드 17763.316)</li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><strong>Microsoft 정보 거버넌스</strong></td>
<td>  다음에 대한 원격 지침을 제공합니다.
<ul>
<li>  보존 레이블 및 정책.  </li>
<li>  레코드 관리.  </li>
<li>  삭제 정책.  </li>
<li>  커뮤니케이션 규정 준수.  </li>
<li>  참가자 위험 관리.  </li>
<li>  Advanced eDiscovery.  </li>
</ul>

  <strong>다음은 범위를 벗어나는 예제입니다. </strong>  
<ul>
<li> 레코드 관리 파일 계획 개발</li>
<li> 데이터 커넥터</li>
<li> 정보 장벽.</li>
<li> 권한이 부여된 액세스 관리.</li>
<li> SharePoint의 정보 아키텍처 개발.</li>
<li> 사용자 지정 스크립팅 및 코딩.</li>
</td>
<td>일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 최소 시스템 요구 사항은 없습니다.</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Information Protection</strong></td>
<td>  다음에 대한 원격 지침을 제공합니다.
<ul>
<li>  데이터 분류.  </li>
<li>  민감 정보 유형  </li>
<li>  민감도 레이블의 만들기  </li>
<li>  민감도 레이블 적용  </li>
<li>  통합 레이블 구성  </li>
<li>  교육 가능한 분류자  </li>
<li>  콘텐츠 탐색기와 활동 탐색기를 사용하여 데이터 확인  </li>
<li>  정책을 사용하여 레이블 게시(수동 및 자동)  </li>
<li>  Microsoft Teams 채팅 및 채널에 대한 DLP(데이터 손실 방지) 정책 생성.  </li>
<li>  Windows 10 장치에 대한 끝점 DLP 정책 만들기  </li>
</ul>

<strong>다음은 범위를 벗어나는 예제입니다. </strong>  
<ul>
<li>고객 키.</li>
<li>중요한 정보 유형에 대한 사용자 지정 정규식(RegEx) 개발</li>
<li>키워드 사전 만들기 또는 수정</li>
<li>사용자 지정 스크립팅 및 코딩.</li>
</ul>
<strong>참고:</strong> 자세한 내용은 Enterprise Mobility + Security의 <strong>Azure Information Protection을</strong> <a href="#enterprise-mobility--security">참조하세요.</a>
<ul>

</td>
<td>일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 최소 시스템 요구 사항은 없습니다.</td>
</tr>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  앱 및 장치에 대한 클라우드 기반 MDM(모바일 장치 관리) 및 MAM(모바일 앱 관리) 공급자로 Intune을 사용할 준비를 위한 원격 지침을 제공합니다. 정확한 단계는 원본 환경에 따라 다르며 모바일 장치와 모바일 앱 관리 요구 사항에 기반합니다. 해당 단계는 다음과 같습니다.
<ul>
<li>  최종 사용자에게 라이선스 부여  </li>
<li>  Intune에서 사용할 ID를 구성하는 데 사용할 ID는 Azure AD(클라우드 ID)를 활용합니다.  </li>
<li>  Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기  </li>
<li>  다음을 비롯한 관리 요구에 따라 MDM 기관 구성
<ul>
<li>  Intune이 유일한 MDM 솔루션인 경우 Intune을 MDM 기관으로 설정  </li>
</ul></li>
<li>  MDM 지침 제공:
<ul>
<li>  MDM 관리 정책의 유효성을 검사하는 데 사용할 테스트 그룹 구성  </li>
<li>  다음과 같은 MDM 관리 정책 및 서비스 구성
<ul>
<li>  웹 링크 또는 딥 링크를 통해 지원되는 각 플랫폼에 대한 앱 배포.  </li>
<li>  조건부 액세스 정책  </li>
<li>  조직에 기존 인증 기관, 무선 네트워크 또는 VPN 인프라가 있는 경우 전자 메일, 무선 네트워크 및 VPN 프로필 배포.  </li>
<li>  Intune 데이터 웨어하우스에 연결  </li>
<li>  다음에 Intune 통합:
<ul>
<li>  원격 지원을 위한 팀 뷰어(팀 뷰어 구독 필요)  </li>
<li>  MTD(Mobile Threat Defense) 파트너 솔루션(MTD 구독이 필요합니다.  </li>
<li>  통신 비용 관리 솔루션(통신 비용 관리 솔루션 구독 필요)  </li>

</ul></li>
<li>  각 지원되는 플랫폼의 장치를 Intune에 등록합니다.  </li>
</ul></li>
</ul></li>
<li>  앱 보호 지침 제공:
<ul>
<li>  지원되는 각 플랫폼에 대한 Intune 앱 보호 정책 구성  </li>
<li>  관리되는 앱에 대한 조건부 액세스 정책 구성  </li>
<li>  앞서 언급한 MAM 정책을 통해 적절한 사용자 그룹을 대상으로 지정합니다.  </li>
<li>  관리되는 앱 사용 현황 보고서 사용.  </li>
</ul></li>
<li>  레거시 PC 관리에서 Intune MDM으로의 마이그레이션 지침을 제공합니다.  </li>
</ul>
 
</li>
</ul>
  
<strong>클라우드 연결</strong>  

  Intune을 통해 기존 Configuration Manager 환경을 클라우드에 연결할 수 있는 준비를 안내합니다. 정확한 단계는 원본 환경에 따라 다릅니다. 해당 단계는 다음과 같습니다.  
<ul>
<li>  최종 사용자에게 라이선스 부여  </li>
<li>  온-프레미스 Active Directory 및 클라우드 ID를 활용하여 Intune에서 사용할 ID 구성  </li>
<li>  Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기  </li>
<li>  하이브리드 Azure AD 가입을 설정하는 지침을 제공합니다.  </li>
<li>  MDM 자동 등록을 위해 Azure AD를 설정하는 방법에 대한 지침을 제공합니다.  </li>
<li>  원격 인터넷 기반 장치 관리를 공동 관리하기 위한 솔루션으로 사용될 때 클라우드 관리 게이트웨이를 설정하는 방법에 대한 지침을 제공합니다.  </li>
<li>  Intune으로 전환할 지원되는 작업 부하를 구성합니다.  </li>
<li>  Intune에서 등록된 디바이스에서 Configuration Manager 클라이언트를 설치합니다.  </li>
</ul> 

<strong>iOS 및 Android용 Outlook 모바일을 안전하게 배포</strong> 조직에서 iOS 및 Android용 Outlook 모바일을 안전하게 배포하여 사용자가 필요한 모든 앱을 설치하도록 하는 데 도움이 되는 지침을 제공할 수 있습니다.  
  Intune을 통해 iOS 및 Android용 Outlook 모바일을 안전하게 배포하는 단계는 원본 환경에 따라 다를 수 있습니다. 여기에는 다음이 포함됩니다.
<ul>
<li>  Apple App Store 또는 Google Play 스토어를 통해 iOS 및 Android용 Outlook, Microsoft Authenticator 및 Intune 회사 포털 앱을 다운로드합니다.  </li>
<li>  설정에 대한 지침을 제공합니다.
<ul>
<li>  Intune을 사용하여 iOS 및 Android용 Outlook, Microsoft Authenticator 및 Intune 회사 포털 앱을 배포합니다.  </li>
<li>  앱 보호 정책.  </li>
<li>  조건부 액세스 정책  </li>
<li>  앱 구성 정책.  </li>
</ul></li>
</ul>  
  </td>
<td>  IT 관리자는 Intune을 사용하여 무선 네트워크 및 VPN 프로필 배포를 계획할 때 기존 인증 기관, 무선 네트워크 및 VPN 인프라가 프로덕션 환경에서 이미 작동해야 합니다.  
  <strong>참고:</strong>FastTrack 서비스 혜택에는 Intune에 대한 인증 기관, 무선 네트워크, VPN 인프라 또는 Apple MDM 푸시 인증서를 설정하거나 구성하기 위한 지원이 포함되어서는 안 됩니다.  
 
  <strong>참고</strong>: 클라우드 연결 기능을 지원하는 데 필요한 최소 요구 사항에 맞게 Configuration Manager 사이트 서버 또는 Configuration Manager 클라이언트를 설정하거나 업그레이드하기 위한 지원은 FastTrack 서비스 혜택에 포함되지 않습니다. 이에 대한 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">지원은 Microsoft 파트너에게</a> 문의하세요.

  <strong>Microsoft Defender ATP(Advanced Threat Protection)에 통합된 Intune</strong> 
 
  <strong>참고:</strong>Microsoft Defender ATP와 Intune을 통합하고 Windows 10 위험 수준 평가를 기반으로 장치 준수 정책을 만드는 데 도움을 제공합니다. 구매, 라이선스 또는 정품 인증에 대한 지원은 제공하지 않습니다. 이에 대한 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">지원은 Microsoft 파트너에게</a> 문의하세요.  
  
<strong>Windows Autopilot</strong> 
 
  IT 관리자는 하드웨어 공급 업체가 사용자를 대신하여 하드웨어 ID를 업로드하거나 Windows Autopilot 서비스로 업로드하는 방법으로 조직에 장치를 등록합니다.  
  
</td>
</tr>

<tr class="odd">
<td><strong>Office 365 Advanced Threat Protection (ATP)</strong></td>
<td>  다음에 대한 원격 지침을 제공합니다.
<ul>
<li>  안전한 링크, 안전한 첨부 파일 및 피싱 방지 사용.  </li>
<li>  자동화, 조사 및 대응 구성.  </li>
<li>  공격 시뮬레이터 사용.  </li>
<li>  보고 및 위협 분석.  </li>
</ul></td>
<td>일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 최소 시스템 요구 사항은 없습니다.</td>
</tr>
</tbody>
</table>

## <a name="office-365"></a>Office 365

<<table>
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
<td>  Exchange Online의 경우 조직에서 전자 메일을 사용할 수 있도록 준비하는 프로세스를 안내합니다. 정확한 단계는 원본 환경 및 전자 메일 마이그레이션 계획에 따라 다를 수 있습니다.  
  다음에 대한 원격 지침을 제공합니다.
<ul>
<li>  Office 365에서 유효성이 검사된 모든 메일 사용이 가능한 도메인에 대해 EOP(Exchange Online Protection) 기능을 설정합니다.  </li>
<li>  MX(메일 교환) 레코드를 Office 365로 설정  </li>
<li>  구독 서비스의 일부인 경우 Office 365 ATP 기능 설정 자세한 내용은 이 표의 <strong>Office 365 Advanced Threat Protection</strong> 부분을 참조하세요.  </li>
<li>  구독 서비스의 일부로 Office 365에서 확인된 모든 메일 사용 가능 도메인에 대한 데이터 손실 방지(DLP) 기능 설정. MX 레코드가 Office 365를 가리키면 완료됩니다.</li>
<li>  구독 서비스의 일부로 Office 365에서 확인된 모든 메일 사용 가능 도메인에 대해 Office 365 메시지 암호화(OME)를 설정합니다. MX 레코드가 Office 365를 가리키면 완료됩니다.</li>
</ul>
  <strong>참고:</strong> MRS(사서함 복제 서비스)가 IRM(정보 권한 관리) 전자 메일을 해당 Exchange Online 사서함으로 마이그레이션하려고 합니다. 마이그레이션 후 보호된 콘텐츠를 읽는 기능은 클라이언트가 AD RMS(Active Directory Rights Managed Services) 서식 파일을 Azure RMS(Azure Rights Management Service)에 매핑하고 복사하는 방법에 따라 다릅니다.  
<ul>
<li>  방화벽 포트 구성  </li>
<li>  필요한 자동 검색, SPF(보낸 사람 정책 프레임워크), 도메인 키 식별 메일(DKIM), 도메인 기반 메시지 인증, 보고 및 적합성(DMARC) 및 MX 레코드(필요한 경우)를 비롯한 DNS 설정  </li>
<li>  원본 메시징 환경과 Exchange Online 간 전자 메일 흐름 설정(필요한 경우)  </li>
<li>  원본 메시징 환경에서 Office 365로 메일 마이그레이션 수행  </li>
<li>  사서함 클라이언트(Windows용 Outlook, 웹용 Outlook, iOS 및 Android용 Outlook) 구성  </li>
</ul>
  <strong>데이터 마이그레이션</strong>  <br>
Office 365로의 데이터 마이그레이션에 FastTrack 혜택 사용에 대한 자세한 내용은 데이터 <a href="https://docs.microsoft.com/fasttrack/data-migration">마이그레이션을 참조하세요.</a>   
<td>  원본 환경에는 다음 최소 수준 중 하나만 있어야 합니다.
<ul>
<li>  Exchange Server 2003 이후 버전을 사용하는 단일 또는 다중 Exchange 조직  </li>
<li>  단일 IMAP(Internet Message Access Protocol) 지원 전자 메일 환경  </li>
<li>  단일 G 제품군 환경(Gmail, 연락처 및 캘린더만)  </li>
<li>  Multi-Geo 기능에 대한 자세한 내용은 <a href="https://go.microsoft.com/fwlink/?linkid=872776">Exchange Online의 Multi-Geo 기능을 참조하세요.</a>  </li>
</ul>
Project for Office 365, Windows용 Outlook, iOS 및 Android용 Outlook, 비즈니스용 OneDrive 동기화 클라이언트, Power BI Desktop 및 비즈니스용 Skype와 같은 온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office의</a>시스템 요구 사항에 정의된 최소 수준에 있어야 합니다.  </td>
</tr>
<tr class="even">
<td><strong>Microsoft 정보 거버넌스</strong></td>
<td>  다음에 대한 원격 지침을 제공합니다.
<ul>
<li>  보존 레이블 및 정책.  </li>
<li>  레코드 관리.  </li>
<li>  삭제 정책.  </li>
<li>  커뮤니케이션 규정 준수.  </li>
<li>  참가자 위험 관리.  </li>
<li>  Advanced eDiscovery.  </li>
</ul>

  <strong>다음은 범위를 벗어나는 예제입니다. </strong>  
<ul>
<li> 레코드 관리 파일 계획 개발</li>
<li> 데이터 커넥터</li>
<li> 정보 장벽.</li>
<li> 권한이 부여된 액세스 관리.</li>
<li> SharePoint의 정보 아키텍처 개발.</li>
<li> 사용자 지정 스크립팅 및 코딩.</li>
</td>
<td>일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 최소 시스템 요구 사항은 없습니다.</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Information Protection</strong></td>
<td>  다음에 대한 원격 지침을 제공합니다.
<ul>
<li>  데이터 분류.  </li>
<li>  민감 정보 유형  </li>
<li>  민감도 레이블의 만들기  </li>
<li>  민감도 레이블 적용  </li>
<li>  통합 레이블 구성  </li>
<li>  교육 가능한 분류자  </li>
<li>  콘텐츠 탐색기와 활동 탐색기를 사용하여 데이터 확인  </li>
<li>  정책을 사용하여 레이블 게시(수동 및 자동)  </li>
<li>  Microsoft Teams 채팅 및 채널에 대한 DLP(데이터 손실 방지) 정책 생성.  </li>
<li>  Windows 10 장치에 대한 끝점 DLP 정책 만들기  </li>
</ul>

<strong>다음은 범위를 벗어나는 예제입니다. </strong>  
<ul>
<li>고객 키.</li>
<li>중요한 정보 유형에 대한 사용자 지정 정규식(RegEx) 개발</li>
<li>키워드 사전 만들기 또는 수정</li>
<li>사용자 지정 스크립팅 및 코딩.</li>
</ul>
<strong>참고:</strong> 자세한 내용은 Enterprise Mobility + Security의 <strong>Azure Information Protection을</strong> <a href="#enterprise-mobility--security">참조하세요.</a>
<ul>

</td>
<td>일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 최소 시스템 요구 사항은 없습니다.</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  다음에 대한 원격 지침을 제공합니다.
<ul>
<li>  Teams를 지원하기 위한 Exchange Online, SharePoint Online, Office 365 그룹 및 Azure AD의 최소 요구 사항 확인  </li>
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
<li>  Teams 앱 정책 구성(Teams 웹 앱, Teams 데스크톱 앱 및 iOS 및 Android 앱용 Teams)  </li>
</ul>
해당하는 경우 다음에 대한 지침도 제공합니다.
<ul>
<li>  Microsoft Teams 룸 디바이스:  </li>
<ul>
<li>  <a href="https://go.microsoft.com/fwlink/?linkid=2066478">팀 장치 카탈로그</a>에 나열된 지원되는 전화 및 회의실 디바이스에 필요한 온라인 계정 생성.  </li>
<li>  인증된 Microsoft Teams 룸 장치의 서비스 쪽 구성에 대한 원격 지원.  </li>
<li>  오디오 회의 사용:  </li>
<li>  회의 브리지 기본 설정에 대한 조직 설정  </li>
<li>  회의 브리지를 라이선스가 있는 사용자에게 할당  </li>
</ul>
<li>  전화 시스템:
<ul>
<li>  클라우드 음성 기본 설정에 대한 조직 설정  </li>
<li>  통화 플랜<a href="https://go.microsoft.com/fwlink/?linkid=2066478">지침(사용 가능한 시장):</a>
<ul>
<li>  라이선스가 있는 사용자에게 번호 할당  </li>
<li>  UI(사용자 인터페이스)를 통해 최대 999개의 지역 번호 이식 지침  </li>
<li>  999개가 넘는 번호를 지원하는 지역 번호 이식 SR(서비스 요청)  </li>
</ul></li>
<li>  직접 라우팅 지침:
<ul>
<li>  파트너 호스팅 시나리오의 직접 라우팅 디자인 또는 최대 10개 사이트에 대한 고객 배포 시나리오에 대한 조직 설정 지침입니다.  </li>
<li> SBC(Session Border Controller) 구성 검토. </li>

<li> 다이얼 플랜 구성에 대한 원격 지원. </li>

<li> 음성 경로 구성</li>

<li> 미디어 우회 및 로컬 미디어 최적화. </li>

</ul></li>
</ul></li>
<li>  권한 부여 팀 라이브 이벤트  </li>
<li>  조직 설정 및 Microsoft Stream에 통합  </li>
<li>  비즈니스용 Skype에서 Teams로의 전환에 대한 지침입니다.  </li>
</ul></td>
<td><ul>
<li>  Office 365용 Azure AD에서 사용하도록 설정된 ID입니다.  </li>
<li>  SharePoint Online에 대해 사용하는 사용자.  </li>
<li>  Exchange 사서함이 있습니다(Exchange 하이브리드 구성의 온라인 및온-프레미스).  </li>
<li>  Office 365 그룹에서 사용되도록 설정됩니다.  </li>
</ul>
  <strong>참고:</strong> 사용자가 SharePoint Online 라이선스를 할당하고 사용하도록 설정하지 않은 경우 Office 365에 비즈니스용 OneDrive 저장소가 없습니다. 파일 공유는 채널에서 계속 작동하지만 사용자는 Office 365의 비즈니스용 OneDrive 저장소가 없는 채팅에서 파일을 공유할 수 없습니다. Teams는 SharePoint On-premises를 지원하지 않습니다.  <br>
  <strong>참고:</strong> 모든 사용자가 사서함을 Exchange Online에 두는 것이 가장 좋은 상태입니다. 사서함이 있는 사용자는 Azure AD Connect를 통해 Office 365 디렉터리에 ID를 동기화해야 합니다. 이러한 Exchange 하이브리드 고객의 경우 사용자의 사서함이 On-premises인 경우 사용자는 커넥터를 추가하거나 구성할 수 없습니다.  
  Microsoft Teams Windows 및 Mac 데스크톱 클라이언트용 설치 관리자는 <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>에서 다운로드할 수 있습니다.  </td>
</tr>
<tr class="odd">
<td><strong>Office 365 Advanced Threat Protection (ATP)</strong></td>
<td>  다음에 대한 원격 지침을 제공합니다.
<ul>
<li>  안전한 링크, 안전한 첨부 파일 및 피싱 방지 사용.  </li>
<li>  자동화, 조사 및 대응 구성.  </li>
<li>  공격 시뮬레이터 사용.  </li>
<li>  보고 및 위협 분석.  </li>
</ul></td>
<td>일반의 <strong>핵심 온보더링</strong> <a href="#general"></a>부분 외에도 최소 시스템 요구 사항은 없습니다.</td>
</tr>
<tr class="even">
<td><strong>iOS 및 Android용 Outlook</strong></td>
<td>  다음에 대한 원격 지침을 제공합니다.
<ul>
<li>  Apple App Store를 Google Play에서 iOS 및 Android용 Outlook 다운로드  </li>
<li>  계정 구성 및 Exchange Online 사서함 액세스  </li>
<li>  Outlook 모바일 보안(자세한 내용은 <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Exchange Online에서 iOS</a> 및 Android용 Outlook 보안 참조).  </li>
</ul></td>
<td><ul>
<li>  Office 365용 Azure AD에서 사용하도록 설정된 ID입니다.  </li>
<li>  Exchange Online이 구성되고 라이선스가 할당됩니다.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  다음에 대한 원격 지침을 제공합니다.
<ul>
<li>  Power BI 라이선스를 할당합니다.  </li>
<li>  Power BI Desktop 앱을 배포합니다.  </li>
</ul></td>
<td>Power BI Desktop과 같은 온라인 클라이언트 소프트웨어는 Microsoft <a href="https://go.microsoft.com/fwlink/?LinkID=723597">365</a>및 Office의 시스템 요구 사항에 정의된 최소 수준 이상이 되어야 합니다.</td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  다음에 대한 원격 지침을 제공합니다.
<ul>
<li>  Project Online이 사용하는 기본 SharePoint 기능 확인  </li>
<li>  테넌트에 Project Online 서비스 추가(사용자에게 구독 추가 포함)  </li>
<li>  ERP(Enterprise 자원 그룹) 설정  </li>
<li>  첫 번째 프로젝트 만들기  </li>
</ul></td>
<td>Project for Office 365와 같은 온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365</a>및 Office에 대한 시스템 요구 사항에 정의된 최소 수준에 있어야 합니다.</td>
</tr>
<tr class="odd">
<td><strong>Project Online Professional 및 Premium</strong></td>
<td>  다음에 대한 원격 지침을 제공합니다.
<ul>
<li>  배포 문제 해결  </li>
<li>  Microsoft 365 관리 센터 및 Windows PowerShell을 사용하여 최종 사용자 라이선스 할당  </li>
<li>  간편 실행을 사용하여 Office 365 포털에서 Project Online 데스크톱 클라이언트 설치  </li>
<li>  Office 365 배포 도구를 사용하여 업데이트 설정 구성  </li>
<li>  Project Online 데스크톱 클라이언트를 위한 단일 사이트에 배포 서버 설정(Office 365 배포 도구용 configuration.xml 파일을 만드는 지침 포함)  </li>
<li>  Project Online 데스크톱 클라이언트을 Project Online Professional 또는 Project Online Premium에 연결합니다.  </li>
</ul></td>
<td>Project for Office 365와 같은 온라인 클라이언트 소프트웨어는 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365</a>및 Office에 대한 시스템 요구 사항에 정의된 최소 수준에 있어야 합니다.</td>
</tr>
<tr class="even">
<td><strong>SharePoint Online 및 비즈니스용 OneDrive</strong></td>
<td>  다음에 대한 원격 지침을 제공합니다.
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
SharePoint 버전에 따라 비즈니스용 OneDrive에 대한 추가 지침이 제공됩니다.
<ul>
<li>  통합 옵션 식별 및 온라인 프레미스 및 온라인 네트워크 인프라 및 대역폭 검토  </li>
<li>  SharePoint Online 2013 SP1 설치(해당되는 경우), 동기화 및 ID 요구 사항을 계획 및 구현하고, 비즈니스용 OneDrive 동기화 클라이언트를 식별합니다.  </li>
<li>  모든 사용자(또는 단계적 롤아웃)에 대한 단일 출시 계획 및 구현  </li>
<li>  라이선스 할당, 내 사이트 및 개인 문서 라이브러리를 Office 365로 리디렉션(SharePoint Online 2013에 해당), 대상 그룹에 OneDrive 액세스 제어(SharePoint Online 2013에 해당) 설정  </li>
<li>알려진 폴더를 OneDrive로 리디렉션하거나 이동합니다.</li>
<li>  비즈니스용 OneDrive 클라이언트 동기화 배포  </li>
</ul>
  <strong>데이터 마이그레이션</strong>  <br>
Office 365로의 데이터 마이그레이션에 FastTrack 혜택 사용에 대한 자세한 내용은 데이터 <a href="https://docs.microsoft.com/fasttrack/data-migration">마이그레이션을 참조하세요.</a>
</ul></td>
<td><br><strong>SharePoint 하이브리드의 경우:</strong>  
<ul>
<li>  SharePoint 하이브리드 구성에는 하이브리드 검색, 사이트, 세분화, 콘텐츠 형식, 비즈니스용 OneDrive, 확장된 앱 시작 프로그램, 엑스트라넷 사이트 및 온라인에서 단일 대상 SharePoint Online 환경으로 연결된 셀프 서비스 사이트 만들기 구성이 포함됩니다.  </li>
</ul>
  <strong>참고:</strong> 셀프 서비스 사이트 만들기는 SharePoint 2013을 실행하는 On-프레미스 서버의 범위에 있지 않습니다.  
<ul>
<li>  SharePoint 하이브리드를 사용하도록 설정하려면 다음의 On-premises SharePoint Server 환경, 2013, 2016 또는 2019 중 하나를 설정해야 합니다.  </li>
</ul>
  <strong>참고:</strong> SharePoint Server로의 On-premises SharePoint 환경 업그레이드는 범위에 있지 않습니다. Microsoft 파트너에게 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">지원을</a> 요청하세요. 자세한 내용은 SharePoint 하이브리드 기능에 대한 최소 공개 업데이트 <a href="https://go.microsoft.com/fwlink/?linkid=853548">수준을 참조하세요.</a><em></em>  <br>
  <strong>참고:</strong> Multi-Geo 기능에 대한 자세한 내용은 <a href="https://go.microsoft.com/fwlink/?linkid=831056">Office 365의 OneDrive 및 SharePoint Online의 Multi-Geo 기능을 참조하세요.</a><em></em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td><ul>
Yammer Enterprise 서비스를 사용하도록 설정하기 위한 원격 지침을 제공합니다.  
</ul></td>
<td>온라인 클라이언트 소프트웨어는 Microsoft 365 및 Office의 시스템 요구 사항에 정의된 최소 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">수준 이상이 되어야 합니다.</a></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Enterprise Mobility + Security

<table>
<thead>
<tr class="header">
<th><strong>서비스</strong></th>
<th><strong>FastTrack 지침 세부 정보</strong></th>
<th><strong>원본 환경 기대치</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Azure AD(Azure Active Directory) 및 Azure AD Premium</strong></td>
<td>  다음 시나리오에서 클라우드 ID를 보호하는 데 필요한 원격 지침을 제공합니다.  

 <br/>

<strong>보안 기본 인프라</strong>  </ul>
<ul>
<li>  Azure MFA(Multi-Factor Authentication)(클라우드 전용), Microsoft Authenticator 앱 및 Azure MFA 및 SSPR(셀프 서비스 암호 재설정)에 대한 결합 등록을 포함하여 ID에 대해 강력한 인증을 구성하고 사용하도록 설정  </li>
<li>  Azure AD Premium이 아닌 고객의 경우 보안 기본값을 사용하여 ID를 보호할 수 있는 지침이 제공됩니다.  </li>
<li>  Azure AD 프리미엄 고객의 경우 조건부 액세스로 ID를 보호할 수 있는 지침이 제공됩니다.  </li>
<li>  Azure AD 암호 보호를 사용하여 취약한 암호의 사용을 감지하고 차단합니다.  </li>
<li>  Azure AD 응용 프로그램 프록시를 사용하여 프레미스 웹앱에 대한 원격 액세스 보안  </li>
<li>  Azure ID 보호를 사용하여 위험 기반 검색 및 수정을 사용하도록 설정  </li>
<li>  사용자 지정 브랜드가 있는 로고, 텍스트 및 이미지를 포함하여 사용자 지정 로그인 화면 사용  </li>
<li>  Azure AD B2B를 사용하여 게스트 사용자와 앱 및 서비스를 안전하게 공유합니다.  </li>
<li>  RBAC(역할 기반 액세스 제어) 기본 제공 관리 역할을 사용하여 Office 365 관리자에 대한 액세스를 관리하고 권한 있는 관리자 계정 수를 줄입니다.  </li>
<li>  하이브리드 Azure AD 조인 구성  </li>
<li>  Azure AD 가입 구성  </li>
</ul>
  
<strong>모니터링 및 보고</strong>  
<ul>
<li>  
  Azure AD Connect Health를 사용하여 AD FS, Azure AD Connect 및 도메인 컨트롤러에 대한 원격 모니터링을 사용하도록 설정  
  </li>
</ul>
  
<strong>거버넌스</strong>  
<ul>
<li>  
  Azure AD 권리 부여 관리를 사용하여 Azure AD ID 및 액세스 수명 주기를 대규모로 관리합니다.
  </li>
<li>  
  Azure AD 액세스 검토를 사용하여 Azure AD 그룹 구성원 자격, 엔터프라이즈 앱 액세스 및 역할 할당 관리  
  </li>
<li>  
  Azure AD 사용 약관 검토  
  </li>
<li>  
  Azure AD Privileged Identity Management를 사용하여 권한 있는 관리자 계정에 대한 액세스를 관리하고 제어합니다.  
  </li>
</ul>
  
<strong>자동화 및 효율성 </strong>  
<ul>
<li>  
  Azure AD SSPR 사용  
  </li>
<li>  사용자가 Azure AD 셀프 서비스 그룹 관리를 사용하여 자체 클라우드 보안 또는 Office 365 그룹을 만들고 관리할 수 있도록 허용  </li>
<li>  Azure AD 위임된 그룹 관리를 사용하여 엔터프라이즈 앱에 대한 위임된 액세스 관리  </li>
<li>  Azure AD 동적 그룹을 사용하도록 설정  </li>
<li>  컬렉션을 사용하여 내 앱 포털에서 앱 구성  </li>
</ul></td>
<td>Azure AD 및 Azure AD Premium 기능과의 통합을 방지하는 식별된 문제의 수정을 포함하여 Azure AD Premium에 대한 On-premises Active Directory 및 해당 환경이 준비되었습니다.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection </strong></td>
<td>  다음에 대한 원격 지침을 제공합니다.
<ul>
<li>  테넌트 활성화 및 구성  </li>
<li>  레이블과 정책 만들기 및 설정  </li>
<li>  문서에 정보 보호 적용  </li>
<li>  Azure Information Protection 클라이언트를 사용하여 Windows에서 실행 중인 Office 앱(Word, PowerPoint, Excel, Outlook 등)에서 자동으로 정보 분류 및 레이블 지정  </li>
<li>  Azure Information Protection 스캐너를 사용하여 미사용 파일 검색 및 레이블 지정  </li>
<li>  Exchange Online 메일 흐름 규칙을 사용하여 전송 중인 전자 메일 모니터링  </li>
</ul>
Microsoft Azure RMS(권한 관리 서비스), OME(Office 365 메시지 암호화) 및 DLP(데이터 손실 방지)를 사용하여 보호를 적용하려는 경우도 지침을 제공합니다.  </td>
<td>  고객 선행 요구 사항 책임은 다음과 같습니다.
<ul>
<li>  검사할 파일 공유 위치 목록입니다.  </li>
<li>  승인된 분류 분류입니다. </li>
<li> 키 관리에 대한 규정 제한 또는 요구 사항을 이해합니다.  </li>
<li>  Azure AD와 동기화된,프레미스 Active Directory에 대해 만들어진 서비스 계정입니다. </li>
<li>  분류 및 보호를 위해 구성된 레이블입니다. </li>
<li> Azure Information Protection 스캐너에 대한 모든 선행이 준비됩니다. 자세한 내용은 Azure Information Protection 통합 레이블 지정 스캐너를 설치 및 배포하기 위한 선행 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">구성을 참조하세요.</a> </li>
<li>  사용자 장치가 지원되는 운영 체제를 실행하고 있으며 필수 필수가 설치되어 있는지 확인합니다. 자세한 내용은 다음을 참조합니다.</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">관리자 가이드: 사용자를 위한 Azure Information Protection 통합 레이블 지정 클라이언트 설치</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">iOS 또는 Android용 Azure Information Protection 앱은 무엇입니까?</a>  </li>
</ul>
<li> 하이브리드 지원을 위한 AD RMS(Active Directory RMS) 커넥터를 포함하여 Azure RMS 커넥터 및 서버의 설치 및 구성  </li>
<li> 배포에 이러한 옵션 중 하나를 필요로 하는 경우 BYOK(Bring Your Own Key), DKE(이중 키 암호화)(통합 레이블 지정 클라이언트만 해당) 또는 HYOK(Own Key)를 설치 및 구성합니다.  </li>
  </ul>
</ul>
  
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  앱 및 장치에 대한 클라우드 기반 MDM(모바일 장치 관리) 및 MAM(모바일 앱 관리) 공급자로 Intune을 사용할 준비를 위한 원격 지침을 제공합니다. 정확한 단계는 원본 환경에 따라 다르며 모바일 장치와 모바일 앱 관리 요구 사항에 기반합니다. 해당 단계는 다음과 같습니다.
<ul>
<li>  최종 사용자에게 라이선스 부여  </li>
<li>  Intune에서 사용할 ID를 구성하는 데 사용할 ID는 Azure AD(클라우드 ID)를 활용합니다.  </li>
<li>  Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기  </li>
<li>  다음을 비롯한 관리 요구에 따라 MDM 기관 구성
<ul>
<li>  Intune이 유일한 MDM 솔루션인 경우 Intune을 MDM 기관으로 설정  </li>
</ul></li>
<li>  MDM 지침 제공:
<ul>
<li>  MDM 관리 정책의 유효성을 검사하는 데 사용할 테스트 그룹 구성  </li>
<li>  다음과 같은 MDM 관리 정책 및 서비스 구성
<ul>
<li>  웹 링크 또는 딥 링크를 통해 지원되는 각 플랫폼에 대한 앱 배포.  </li>
<li>  조건부 액세스 정책  </li>
<li>  조직에 기존 인증 기관, 무선 네트워크 또는 VPN 인프라가 있는 경우 전자 메일, 무선 네트워크 및 VPN 프로필 배포.  </li>
<li>  Intune 데이터 웨어하우스에 연결  </li>
<li>  다음에 Intune 통합:
<ul>
<li>  원격 지원을 위한 팀 뷰어(팀 뷰어 구독 필요)  </li>
<li>  MTD(Mobile Threat Defense) 파트너 솔루션(MTD 구독이 필요합니다.  </li>
<li>  통신 비용 관리 솔루션(통신 비용 관리 솔루션 구독 필요)  </li>
</ul></li>
<li>  각 지원되는 플랫폼의 장치를 Intune에 등록합니다.  </li>
</ul></li>
</ul></li>
<li>  앱 보호 지침 제공:
<ul>
<li>  지원되는 각 플랫폼에 대한 Intune 앱 보호 정책 구성  </li>
<li>  관리되는 앱에 대한 조건부 액세스 정책 구성  </li>
<li>  앞서 언급한 MAM 정책을 통해 적절한 사용자 그룹을 대상으로 지정합니다.  </li>
<li>  관리되는 앱 사용 현황 보고서 사용.  </li>
</ul></li>
<li>  레거시 PC 관리에서 Intune MDM으로의 마이그레이션 지침을 제공합니다.  </li>
</ul>
  
</li>
</ul>
  
<strong>클라우드 연결</strong>  

  Intune을 통해 기존 Configuration Manager 환경을 클라우드에 연결할 수 있는 준비를 안내합니다. 정확한 단계는 원본 환경에 따라 다릅니다. 해당 단계는 다음과 같습니다.  
<ul>
<li>  최종 사용자에게 라이선스 부여  </li>
<li>  온-프레미스 Active Directory 및 클라우드 ID를 활용하여 Intune에서 사용할 ID 구성  </li>
<li>  Intune 구독에 사용자 추가, IT 관리자 역할 정의, 사용자 및 디바이스 그룹 만들기  </li>
<li>  하이브리드 Azure AD 가입을 설정하는 지침을 제공합니다.  </li>
<li>  MDM 자동 등록을 위해 Azure AD를 설정하는 방법에 대한 지침을 제공합니다.  </li>
<li>  원격 인터넷 기반 장치 관리를 공동 관리하기 위한 솔루션으로 사용될 때 클라우드 관리 게이트웨이를 설정하는 방법에 대한 지침을 제공합니다.  </li>
<li>  Intune으로 전환할 지원되는 작업 부하를 구성합니다.  </li>
<li>  Intune에서 등록된 디바이스에서 Configuration Manager 클라이언트를 설치합니다.  </li>
</ul> 

<strong>iOS 및 Android용 Outlook 모바일을 안전하게 배포</strong> 조직에서 iOS 및 Android용 Outlook 모바일을 안전하게 배포하여 사용자가 필요한 모든 앱을 설치하도록 하는 데 도움이 되는 지침을 제공할 수 있습니다.  
  Intune을 통해 iOS 및 Android용 Outlook 모바일을 안전하게 배포하는 단계는 원본 환경에 따라 다를 수 있습니다. 여기에는 다음이 포함됩니다.
<ul>
<li>  Apple App Store 또는 Google Play 스토어를 통해 iOS 및 Android용 Outlook, Microsoft Authenticator 및 Intune 회사 포털 앱을 다운로드합니다.  </li>
<li>  설정에 대한 지침을 제공합니다.
<ul>
<li>  Intune을 사용하여 iOS 및 Android용 Outlook, Microsoft Authenticator 및 Intune 회사 포털 앱을 배포합니다.  </li>
<li>  앱 보호 정책.  </li>
<li>  조건부 액세스 정책  </li>
<li>  앱 구성 정책.  </li>
</ul></li>
</ul>  
  </td>
<td>  IT 관리자는 Intune을 사용하여 무선 네트워크 및 VPN 프로필 배포를 계획할 때 기존 인증 기관, 무선 네트워크 및 VPN 인프라가 프로덕션 환경에서 이미 작동해야 합니다.  
  <strong>참고:</strong>FastTrack 서비스 혜택에는 Intune에 대한 인증 기관, 무선 네트워크, VPN 인프라 또는 Apple MDM 푸시 인증서를 설정하거나 구성하기 위한 지원이 포함되어서는 안 됩니다.  
 
  <strong>참고</strong>: 클라우드 연결 기능을 지원하는 데 필요한 최소 요구 사항에 맞게 Configuration Manager 사이트 서버 또는 Configuration Manager 클라이언트를 설정하거나 업그레이드하기 위한 지원은 FastTrack 서비스 혜택에 포함되지 않습니다. 이에 대한 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">지원은 Microsoft 파트너에게</a> 문의하세요.

  <strong>Microsoft Defender ATP(Advanced Threat Protection)에 통합된 Intune</strong> 
 
  <strong>참고:</strong>Microsoft Defender ATP와 Intune을 통합하고 Windows 10 위험 수준 평가를 기반으로 장치 준수 정책을 만드는 데 도움을 제공합니다. 구매, 라이선스 또는 정품 인증에 대한 지원은 제공하지 않습니다. 이에 대한 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">지원은 Microsoft 파트너에게</a> 문의하세요.  
  
<strong>Windows Autopilot</strong> 
 
  IT 관리자는 하드웨어 공급 업체가 사용자를 대신하여 하드웨어 ID를 업로드하거나 Windows Autopilot 서비스로 업로드하는 방법으로 조직에 장치를 등록합니다.  
  
</td>
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
<td>  Windows 7 Professional 및 Windows 8.1 Professional에서 Windows 10 Enterprise로 업그레이드하기 위한 지침을 제공합니다.  
  다음에 대한 원격 지침을 제공합니다.
<ul>
<li>  Windows 10 의도 이해  </li>
<li>  원본 환경 및 요구 사항 평가(Windows 10 배포를 지원하기 위해 Microsoft Endpoint Configuration Manager를 필요한 수준으로 업그레이드해야 합니다).  </li>
<li>  Microsoft Endpoint Configuration Manager 또는 Microsoft 365를 사용하여 Windows 10 Enterprise 및 Microsoft 365 앱을 배포합니다.  </li>
<li>  Windows 10 앱을 평가할 수 있는 권장 옵션입니다.  </li>
<li>  Desktop Analytics 배포 계획 생성을 통해 Desktop Analytics 및 지침을 사용할 수 있습니다.  </li>
<li>  Configuration Manager에서 Office 365 준비 대시보드를 활용하거나 Office용 독립 실행형 준비 Toolkit Microsoft 365 앱 배포를 지원하여 Microsoft 365 앱 호환성 평가.  </li>
<li>  성공적인 배포를 위해 원본 환경을 최소 요구 사항까지 설정하기 위해 필요한 사항에 대한 재구성 검사 목록을 만들 수 있습니다.  </li>
<li>  필요한 장치 하드웨어 요구 사항을 충족하는 경우 기존 장치에 대한 업그레이드 지침을 Windows 10 Enterprise로 제공합니다.  </li>
<li>  기존 배포 움직임을 지원하기 위한 업그레이드 지침을 제공합니다. FastTrack은 Windows 10으로의 준비된 업그레이드를 위한 지침을 권장하고 제공합니다. Windows 정리 이미지 설치 및 Windows Autopilot 배포 시나리오에서도 지침을 사용할 수 있습니다.  </li>
<li>  Windows 10 배포의 일부로 Configuration Manager를 사용하여 Microsoft 365 앱을 배포합니다.   </li>
<li>  조직이 기존 Configuration Manager 환경 또는 Microsoft 365를 사용하여 Windows 10 Enterprise 및 Microsoft 365 앱을 최신으로 유지 하는 데 도움이 되는 지침을 제공합니다.  </li>
</ul>
  <strong>다음은 범위를 벗어나는 예제입니다. </strong>  
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
Microsoft 파트너에게 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">이러한</a> 서비스에 대한 지원을 요청하세요.  </td>
<td>  PC 업그레이드의 경우, 다음 요구 사항을 충족해야 합니다.
<ul>
<li>  원본 OS: Windows 7 Enterprise 또는 Professional, Windows 8.1 Enterprise 또는 Professional  </li>
<li>  장치: 데스크톱, 전자 필기장 또는 태블릿 폼 팩터.  </li>
<li>  대상 OS: 창 10 Enterprise.  </li>
</ul>
인프라 업그레이드의 경우, 다음 요구 사항을 충족해야 합니다.
<ul>
<li>  Microsoft Endpoint Configuration Manager.  </li>
<li>  Configuration Manager 버전은 Windows 10 대상 버전에서 지원해야 합니다. 자세한 내용은 <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager에서 Windows 10 지원</a>에서 Configuration Manager 지원 표를 참조하세요.  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP)는 엔터프라이즈 네트워크가 고급 위협을 방지, 탐지, 조사 및 대응하는 데 도움이 되도록 설계된 플랫폼입니다.  
  다음에 대한 원격 지침을 제공합니다.
<ul>
<li>  끝점을 보호하는 기술을 배포합니다.  </li>
<li>  끝점 보호 및 장치 제한 프로필 구성  </li>
<li>  OS 버전 및 장치 관리(Intune, Microsoft Endpoint Configuration Manager, GPOS(그룹 정책 개체) 및 타사 구성 포함) 및 Windows Defender AV 서비스 또는 기타 끝점 보안 소프트웨어의 상태를 평가합니다.  </li>
<li>  Windows AV 서비스 또는 기타 끝점 보안 소프트웨어의 상태 평가  </li>
<li>  네트워크 트래픽을 제한하는 Proxies 및 방화벽 평가  </li>
<li>  온보딩 끝점을 사용하여 ATP 에이전트 프로필을 배포하는 방법을 설명하여 Microsoft Defender ATP 서비스를 사용하도록 설정  </li>
<li>  다음에 대한 배포 지침, 구성 지원 및 교육:
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
<li> Microsoft Defender ATP(Windows E5 또는 Microsoft 365 E5 라이선스 필요)  </li>
<li>  
  보안 점수.  
  </li>
</ul></li>
<li>  시뮬레이션 및 자습서 검토(예: 연습 시나리오, 가짜 맬웨어 및 자동화된 조사).  </li>
<li>  보고 및 위협 분석 기능 개요  </li>
<li>  Office 365 ATP와 Microsoft Defender ATP 통합.  </li>
<li>  Microsoft Defender 보안 센터 포털 탐색.  </li>
<li>  다음 운영 체제는 다음과 같습니다.
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
  Windows Server 2019 Core Edition  
  </li>
<li>  
  Windows Server Semi-Annual 채널(SAC) 버전 1803.  
  </li>
<li>  
  macOS 버전 10.13, 10.14 및 10.15.  
  </li>
</ul>
</li>
</ul>
<strong>참고:</strong> 모든 Windows Server 버전은 최신 버전의 System Center Configuration Manager 2012(버전 1012 R2, 1511 또는 1602) 또는 Microsoft Endpoint Configuration Manager(버전 2002 이상)에서 관리해야 합니다. 

</li>
</ul>

<strong>다음은 범위를 벗어나는 예제입니다. </strong>  
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
<li>  서버 온보더링 및 구성:
<ul>
<li>  
  오프라인 통신을 위한 프록시 서버 구성  
  </li>
<li>  
  다운 수준 Configuration Manager 인스턴스 및 버전에서 Configuration Manager 배포 패키지 구성  
  </li>
<li>  
  Azure 보안 센터에 서버 온보더링  
  </li>
<li>  
  Configuration Manager에서 관리되지 않는 서버입니다.  
  </li>
</ul></li>
<li>  macOS 온보더링 및 구성:
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
  앱 컨트롤.  
  </li>
<li>  
  악용 방지.  
  </li>
<li>  
  네트워크 방화벽.  
  </li>
</ul></li>
<li>  Microsoft 위협 전문가 등록 또는 구성.  </li>
<li>  API 또는 SIEM(보안 정보 및 이벤트 관리) 연결을 검토하는 구성 또는 교육  </li>
<li>  MTP(Microsoft 위협 방지) 등록 또는 구성.  </li>
<li>  고급 헌팅에 대한 교육 또는 지침.  </li>
<li>  Kusto 쿼리의 사용 또는 생성에 대한 교육 또는 지침입니다.</li>
</li>
</ul>
Microsoft 파트너에게 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">이러한</a> 서비스에 대한 지원을 요청하세요.  
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
<td><p>Windows Virtual Desktop(데스크톱 및 앱 가상화 서비스)에 온보드하기 위한 배포 지침을 제공합니다. Windows Virtual Desktop은 Windows 10 다중 세션 환경을 활용하며 Microsoft 365에 대한 통합 보안 및 관리를 통해 엔터프라이즈용 Microsoft 365 앱에 최적화되어 있습니다.</p>
<p>다음에 대한 원격 지침을 제공합니다.</p>
<ul>
<li>다음을 사용하여 Windows 10 Enterprise 다중 세션 및 엔터프라이즈용 Microsoft 365 앱을 사용하여 Windows Virtual Desktop 환경을 배포합니다.
<ul>
<li>Azure 마켓플레이스 이미지.</li>
<li>공유 이미지.</li>
<li>ODT(Office 배포 Toolkit)</li>
</ul></li>
<li>FSLogix 구성:
<ul>
<li>프로필 컨테이너를 사용하여 FSLogix 에이전트 배포</li>
<li>Office 컨테이너를 통해 FSLogix 에이전트 배포</li>
<li>콘텐츠 제외를 통해 FSLogix 폴더 구성</li>
</ul></li>
<li>Microsoft Edge 배포.</li>
<li>Microsoft Teams 배포.</li>
<li>Windows 가상 데스크톱 클라이언트를 사용하여 연결</li>
</ul>

<strong>다음은 범위를 벗어나는 예제입니다.</strong>
<ul>
<li>고객의 Windows Virtual Desktop 배포 프로젝트 관리</li>
<li>타사 앱 가상화 및 배포</li>
<li>사용자 지정 이미지.</li>
<li>VMware 및 Citrix와 관련된 마이그레이션 및 시나리오</li>
<li>Linux 시나리오.</li>
<li>사용자 프로필 변환 또는 마이그레이션</li>
</ul>
Microsoft 파트너에게 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">이러한</a> 서비스에 대한 지원을 요청하세요.</td>
<td>다음이 이미 있습니다.
<ul>
<li><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop 라이선스 요구 사항.</a></li>
<li>Azure 네트워킹:
<ul>
<li>VNET(가상 네트워크) 만들기 및 서브넷팅</li>
<li>방화벽 및 네트워크 보안 그룹</li>
<li>VPN 및 ExpressRoute.</li>
<li>On-premises에서 Azure로 라우팅</li>
<li>Windows Virtual Desktop에 대한 연결을 허용하는 방화벽 규칙입니다.
</ul>
자세한 내용은 지원되는 원격 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">데스크톱 클라이언트를 참조하세요.</a>
</ul>
<ul><li>Azure AD 일반 설정:
<ul>
<li>ID <i>전략(다음 세</i> 가지 옵션 중 하나만 사용할 수 있습니다.
<ul>
<li>Azure에서 Azure AD Connect가 있는 Active Directory.</li>
<li>VPN 또는 ExpressRoute를 통해 Azure AD Connect가 있는 Active Directory에 대해 Azure AD Connect를 제공합니다.</li>
<li>AD DS(Active Directory 도메인 서비스)</li>
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
<th><strong>원본 환경 기대치</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>앱 보증</strong></td>
<td>  App Assure는 Windows 10 및 Microsoft 365 앱 호환성 문제를 해결하도록 설계된 서비스입니다. App Assure 서비스를 요청하는 경우 적격 구독을 사용할 경우 추가 비용으로 유효한 앱 문제를 해결하기 위해 함께 작업합니다. 또한 Windows Virtual Desktop 및 Microsoft Edge를 배포할 때 호환성 문제가 있는 고객에게 지침을 제공하고 호환성 문제를 해결하기 위한 모든 합리적 노력을 다합니다. 다음 Microsoft 제품에 배포된 앱에 대한 수정 지원을 제공합니다.
<ul>
<li>  <strong>Windows 10(ARM64 </strong> 장치 포함)</li>
<li> <strong>Microsoft 365 앱</strong>  </li>
<li>  <strong>Microsoft Edge -</strong> 배포 지침은 Microsoft Edge 채널 <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">개요를 참조하세요.</a>  </li>
<li>  <strong>Windows 가상 데스크톱</strong> - 자세한 내용은 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">Windows Virtual Desktop이란?</a> 및 Windows 10 Enterprise 다중 세션 <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">FAQ를 참조하세요.</a>  </li>
</ul>

<strong>다음은 범위를 벗어나는 예제입니다. </strong>  
<ul>
<li>  Windows 10 및 Microsoft 365 앱에서 작동하거나 작동하지 않는 기능을 확인하기 위한 앱 인벤토리 및 테스트. 이 프로세스에 관한 자세한 지침을 보려면 <a href="https://go.microsoft.com/fwlink/?linkid=2080140">데스크톱 배포 센터</a>를 방문하세요. 더 심화된 업그레이드 준비 평가에 관심이 있으신 경우 <a href="https://go.microsoft.com/fwlink/?linkid=2053818">최신 데스크톱 평가에 관한 고객 요청</a> 양식을 작성하세요.</li>
<li>  타사 ISV 앱에서 Windows 10 호환성 및 지원 정책 연구 자세한 내용은 <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">데스크톱 분석</a>을 참조하세요.</li>
<li>앱 패키지 전용 서비스. 그렇지만 App Assure 팀은 고객 환경에 배포될 수 있도록 하기 위해 WIndows 10에 대해 수정한 앱을 패키지로 만듭니다.</li>
</ul>

<strong>고객 책임에는 다음이 포함됩니다.</strong>  
<ul>
<li>  앱 목록 만들기.</li>
<li>  Windows 10 및 Microsoft 365 앱에서 앱의 유효성 검증.</li>
</ul>
<strong>참고:</strong>  Microsoft는 소스 코드를 변경할 수 없습니다. 그러나 사용자 앱의 소스 코드를 사용할 수 있는 경우 App Assure 팀이 앱 개발자에게 지침을 제공할 수 있습니다. 


  Microsoft 파트너에게 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">이러한</a> 서비스에 대한 지원을 요청하세요.  </td>

</td>
<td><strong>Windows 10 및 Microsoft 365 앱</strong>
<ul>
<li>  
  Windows 7, Windows 8.1, Office 2010 및 Office 2013에서 작동하는 앱은 Windows 10 및 Microsoft 365 앱에서도 작동합니다.  
  </li>
</ul>
<strong>Windows 10 on ARM</strong>
<ul>
<li>  
Windows 7, Office 2010 이상 버전에서 작동한 앱은 ARM64 장치의 Windows 10 및 Microsoft 365 앱에서도 작동합니다. 
  </li>
</ul>
  <strong>참고:</strong> 
<ul>
<li> x64(64비트) 에뮬ation은 <a href="https://insider.windows.com/">Windows Insider Program에</a>참여하는 고객을 위해 미리 보기에서 사용할 수 있습니다.  </li>
<li>  
 Windows 10 버전 2004 이상에서 Windows가 아닌 고객의 경우 ARM64 Photoshop은 OpenCL 및 OpenGL 호환성 팩을 사용하여 <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">지원됩니다.</a> 
  </li>
<li>  
  Windows Insider Program의 고객은 추가 앱에 사용할 OpenCL 및 OpenGL 호환성 팩의 Insider 버전을 다운로드할 수 있습니다.    
  </li>
</ul>
<strong>Microsoft Edge</strong>
<ul>
<li>  
  웹앱 또는 사이트가 Internet Explorer 11, 지원되는 Google Chrome 버전 또는 모든 버전의 Microsoft Edge에서 작동하면 Microsoft Edge에서도 사용할 수 있습니다.  
  </li>
<li>  
  웹이 지속적으로 진화하고 있는 경우 Microsoft Edge에 대해 게시된 알려진 사이트 호환성에 영향을 미치는 변경 사항 목록을 <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">검토해야 합니다.</a>  
  </li>
</ul>
  <strong>Windows 가상 데스크톱 </strong>  
<ul>
<li>  
  Windows Server RDSH (원격 데스크톱 세션 호스트)에서 실행되는 가상화된 앱도 Windows Virtual Desktop의 일부로 Windows 10 Enterprise 멀티 세션에서 실행됩니다.  
  </li>
<li>  
  Windows 7 또는 Windows 10 VDI(가상 데스크톱 인프라) 환경에서 실행되는 앱은 Windows Virtual Desktop의 일부로 Windows 7 Enterprise 및 Windows 10 Enterprise에서도 실행됩니다.  
  </li>
<li>  
  Windows 7 또는 Windows 10 클라이언트 장치에서 실행되는 앱도 Windows Virtual Desktop의 일부로 Windows 7 Enterprise 및 Windows 10 Enterprise에서 실행됩니다.  
  </li>
</ul>
  <strong>참고:</strong> Windows 10 Enterprise 다중 세션 호환성 제외 및 제한은 다음과 같습니다.
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

## <a name="microsoft-edge"></a>Microsoft Edge


<table>
<thead>
<tr class="header">
<th><strong>서비스</strong></th>
<th><strong>FastTrack 지침 세부 정보</strong></th>
<th><strong>원본 환경 기대치</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Microsoft Edge(Windows</strong> 10 Enterprise 고객용)</td>
<td><ul>
<li>  Microsoft는 Microsoft Endpoint Manager(Microsoft Endpoint Configuration Manager 또는 Intune)를 사용하여 Windows 10 Enterprise에 Microsoft Edge 배포에 대한 원격 배포 지침 및 호환성 지원을 제공합니다.  </li>
<li>  Microsoft Edge 구성(그룹 정책 또는 Intune 앱 구성 및 앱 정책 사용)  </li>
<li>  사이트 목록에서 사용이 필요할 수 있는 사이트 목록을 Internet Explorer 있습니다.  </li>
<li>  기존 엔터프라이즈 Internet Explorer 모드 사용  
  또한 웹 앱 또는 사이트가 Internet Explorer 또는 Google Chrome과 호환되는 경우 추가 비용 없음으로 문제를 해결하기 위한 지침을 제공합니다. 자세한 <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">내용은 App Assure를</a> 참조하세요.  </li>
</ul>

<strong>다음은 범위를 벗어나는 예제입니다. </strong>  
<ul>
<li>고객의 Microsoft Edge 배포에 대한 프로젝트 관리입니다.</li>
<li>  현장 지원.</li>

</td>
<td></td>
</tr>
</tbody>
</table>
