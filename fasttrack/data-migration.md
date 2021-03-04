---
title: 데이터 마이그레이션
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 2/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack은 원본 환경의 메일 및 파일 데이터를 Office 365(Exchange Online, SharePoint Online 및 비즈니스용 OneDrive)로 마이그레이션하는 데 도움이 됩니다. Microsoft가 제공하는 지원 유형은 Office 365 라이선스 수에 따라 다릅니다.
ms.openlocfilehash: b02c7c863cdc689fab4a6545ac1acc84f6b03fc2
ms.sourcegitcommit: cf630a48697177b9cce6c0fbc67a7e7a0b752167
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/03/2021
ms.locfileid: "50416615"
---
# <a name="data-migration"></a>데이터 마이그레이션

FastTrack은 원본 환경의 메일 및 파일 데이터를 Office 365(Exchange Online, SharePoint Online 및 비즈니스용 OneDrive)로 마이그레이션하는 데 도움이 됩니다.

Microsoft가 제공하는 지원 유형은 Office 365 라이선스 수에 따라 달라집니다.

  - **150-499 라이선스를 보유한 Office 365 테넌트**: FastTrack은 마이그레이션 안내만 제공하며 데이터 마이그레이션을 수행해야 합니다. 셀프 서비스 마이그레이션을 수행하기 위해 무료 도구를 계획하고 사용하는 데 도움이 되는 문서를 안내합니다.
  - **라이선스가 500개 이상인 Office 365 테넌트**: FastTrack은 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다. Microsoft는 마이그레이션 계획, 소스 환경 및 Office 365 테넌트 구성, 데이터 마이그레이션 서비스를 활용하여 데이터를 마이그레이션하는 데 도움이 되는 지침을 제공합니다. 마이그레이션 이벤트를 생성하고 예약합니다. 스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다.

> [!NOTE]
> 2017년 9월 1일 이전에 상업용 계획을 구입하거나 갱신한 경우 데이터 마이그레이션 서비스를 받으려면 150개의 라이선스만 있으면 됩니다. 교육 계획의 경우 유급 직원 및 직원 라이선스만 데이터 마이그레이션 서비스를 받을 수 있습니다.

### <a name="considerations"></a>고려 사항

  - Office 365로 데이터를 마이그레이션하려면 소스 환경이 특정 기대치를 충족해야 합니다. Exchange, SharePoint 및 비즈니스용 OneDrive에 대한 소스 환경에 대한 자세한 내용은 [제품 및 기능](products-and-capabilities.md)을 참조합니다.
  - 데이터 마이그레이션 서비스를 제공하려면 소스 환경과 Office 365 테넌트에 대한 적절한 액세스 및 사용 권한이 필요합니다.
  - Microsoft의 데이터 마이그레이션 서비스는 특별한 법적 또는 규제 요건에 따른 데이터용으로 설계되거나 설계되지 않습니다. 데이터를 마이그레이션할 때 FastTrack 마이그레이션 프로젝트에 별도로 제공된 경우를 제외하고, 이 데이터는 시설을 유지하는 모든 위치로 전송, 저장 및 처리될 수 있습니다.
  - 메일 또는 파일 마이그레이션 속도를 보장할 수 없습니다.
  - 소스 환경에서 읽을 수 없거나 손상된 항목과 같은 예기치 않은 문제로 인해 일부 데이터 항목을 마이그레이션하지 못할 수 있습니다.
  - 외부 요인(예: 타사 API(응용 프로그램 프로그래밍 인터페이스) 변경)은 데이터 마이그레이션 서비스의 변경, 지연 또는 중단으로 이어질 수 있습니다.

### <a name="migration-service-availability"></a>마이그레이션 서비스를 사용할 수 있습니다.

  - **상업 및 영국 정부 고객:** 당사는 24시간, 주 7일(24x7) 데이터 마이그레이션 서비스를 제공합니다.
  - **미국 정부/DOD 고객:** 당사는 하루 24시간, 주 5일 영업일(24x5) 데이터 마이그레이션 서비스를 제공합니다.

## <a name="migration-to-exchange-online"></a>Exchange Online으로 마이그레이션

FastTrack을 사용하여 Exchange Online으로 이메일을 마이그레이션하도록 선택하면 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다. Microsoft는 마이그레이션을 계획하고, 소스 환경과 Exchange Online을 구성하고, 데이터 마이그레이션 서비스를 활용하여 편지함을 마이그레이션하는 데 도움이 되는 지침을 제공합니다. 마이그레이션 이벤트를 생성하고 예약합니다. 스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다. 마이그레이션 이벤트가 완료되면 해당 소스 환경의 적절한 예약 및 적격 소스 사서함에서 온 메일이 Exchange Online으로 마이그레이션될 것으로 예상할 수 있습니다.

### <a name="considerations"></a>고려 사항

  - 마이그레이션하기 전에 Exchange Online용 FastTrack 코어 온보딩을 완료해야 합니다.
      - 직접 온보드 탑재를 수행한 경우 필요한 검사 및 필수 구성 요소를 통과해야 합니다. 자세한 내용은 [제품 및 기능](products-and-capabilities.md)을(를) 참조합니다.
  - FastTrack은 활성 Office 365 사서함으로만 마이그레이션합니다.
  - 온-프레미스 Exchange 환경에서 마이그레이션하려면 특정 요구 사항을 충족해야 합니다. 자세한 내용은 [하이브리드 배포 필수 구성 요소](https://go.microsoft.com/fwlink/?LinkId=787528)를 참조합니다.
  - 각 소스 환경은 소스 환경의 각 제품에 대한 최신 서비스 팩(SP) 및 롤업(RU)/누적 업데이트(CU) 레벨에 있어야 합니다.
  - 사내 Active Directory에 있는 메일 그룹(*MailEnabledGroup* 개체) 및 외부 연락처(*MailEnableContact* 개체)는 사서함 데이터 마이그레이션의 일부가 아닙니다. 그러나 Azure AD(Azure Active Directory) 연결을 사용하여 동기화할 수 있습니다. 

## <a name="source-environments"></a>원본 환경

Microsoft의 데이터 마이그레이션 서비스는 다음과 같은 소스 환경에서 데이터를 마이그레이션합니다.

  - Exchange 조직이 하나 또는 여러 개인 Active Directory 포리스트(각 Exchange 메일 시스템은 Exchange 2010 이상이어야 함)입니다.
  - 단일 IMAP 지원 전자 메일 환경
  - G Suite 환경(Gmail, 연락처 및 Outlook 일정만 해당)입니다.

다음 표에서는 각 소스 환경에 대한 마이그레이션 세부 정보를 보여 줍니다.

<table>
<thead>
<tr class="header">
<th><strong>원본 환경</strong></th>
<th><strong>마이그레이션 유형</strong></th>
<th><strong>마이그레이트 대상</strong></th>
<th><strong>마이그레이션되지 않는 사항</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong><br />
<br />
<strong>참고:</strong> On-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</td>
<td>하이브리드 배포를 사용하는 마이그레이션</td>
<td><ul>
<li>전자 메일</li>
<li>서버 쪽 사서함 규칙</li>
<li>위임</li>
<li>사서함 연락처 </li>
<li> 일정 </li>
<li> 작업 </li>
<li> 권한 관리 전자 메일 </li>
<li> 암호화된 전자 메일 </li>
<li> 서명 </li>
<li> 사용자 사서함과 함께 마이그레이션된 개인 보관 파일 </li>
<li> 복구 가능한 항목 </li>
</ul></td>
<td><ul>
<li> 공용 폴더 </li>
<li> 메시지 크기 제한을 초과하는 모든 전자 메일 </li>
<li> 저널링 보관 또는 모든 타사 보관 솔루션 </li>
<li> 차단되거나 비활성 상태인 사용자 </li>
<li> PST(Personal Storage Table) 파일의 보관 데이터 </li>
<li> 손상된 항목 </li>
<li> 비활성 사서함 </li>
<li> 클라이언트 쪽 사서함 규칙</li>
</ul></td>
</tr>
<tr class="even">
<td><strong>G 제품군 환경(Gmail, 연락처 및 캘린더만)</strong><br />
<br />
<strong>참고:</strong> G Suite 환경은 G Suite 마이그레이션 수행에 설명된 선행 <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">요구 사항을 충족해야 합니다.</a></td>
<td>단독형 또는 미리 구성</td>
<td><ul>
<li> 전자 메일 </li>
<li> 사서함 연락처(연락처당 최대 3개의 전자 메일 주소가 마이그레이션됨) </li>
<li> 일정 </li>
<li> 레이블 </li>
</ul></td>
<td><ul>
<li> 규칙 </li>
<li> 위임 </li>
<li> 서명 </li>
<li> 작업 </li>
<li> 메시지 크기 제한을 초과하는 모든 전자 메일 또는 첨부 파일 </li>
<li> 차단되거나 비활성 상태인 사용자 </li>
<li> PST 파일 또는 모든 타사 보관 솔루션(예: Google Vault)의 보관 데이터 </li>
<li> 권한 관리 또는 암호화된 전자 메일 </li>
<li> 손상된 항목 </li>
<li> Google Hangouts** </li>
<li> Google Groups </li>
<li> 리소스 사서함 </li>
<li> 비활성 사서함 </li>
<li> 휴가 설정 및 자동 회신 설정 </li>
<li> 공유 일정, 클라우드 첨부 파일, Google Hangout 링크, 이벤트 색상 </li>
</ul>
**라벨로 저장된 행아웃 대화를 마이그레이트합니다. </td>
</tr>
<tr class="odd">
<td><strong>IMAP4 원본(Domino, GroupWise 또는 Zimbra 등)</strong></td>
<td>기본 IMAP4 도구를 사용한 마이그레이션</td>
<td><li>전자 메일 </li></td>
<td><ul>
<li> 규칙 </li>
<li> 위임 </li>
<li> 메일 그룹 </li>
<li> 외부 연락처 </li>
<li> 메일을 사용하는 사용자 </li>
<li> 차단되거나 비활성 상태인 사용자 </li>
<li> 사서함 연락처 </li>
<li> 일정 </li>
<li> 서명 </li>
<li> 작업 </li>
<li> 메시지 크기 제한을 초과하는 모든 전자 메일 </li>
<li> 보관 데이터 </li>
<li> 암호화된 전자 메일 </li>
<li> 손상된 항목 </li>
<li> 비활성 사서함 </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>FastTrack 책임

Microsoft의 FastTrack 전문가는 마이그레이션 프로젝트 중에 표준 작업을 수행합니다. 자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.

또한 Microsoft의 FastTrack 전문가는 Exchange 마이그레이션과 관련된 다음과 같은 활동을 수행합니다.

  -  해당하는 경우 원본 환경과 Exchange 온라인 간에 SMTP 메일 라우팅 공존을 사용하도록 설정하는 데 도움이 되는 지침을 제공합니다.

## <a name="your-responsibilities"></a>귀하의 책임

마이그레이션 프로젝트 중에 표준 작업을 수행합니다. 자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.

Exchange 마이그레이션과 관련된 다음 작업도 수행합니다.

  - Exchange Online용 FastTrack 코어 온보딩을 완료합니다. 직접 온보드 탑재를 수행한 경우 필요한 검사 및 필수 구성 요소를 통과해야 합니다. 자세한 내용은 [제품 및 기능](products-and-capabilities.md)을(를) 참조합니다.
  -  Office 365 지침에 따라 적절한 수준의 클라이언트 소프트웨어를 설치합니다. 자세한 내용은 [최신 작업 공간](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)를 참조하세요.
  -  사내 Exchange 환경에서 마이그레이션하려는 경우 특정 요구 사항을 충족합니다. 자세한 내용은 [하이브리드 배포 필수 구성 요소](https://go.microsoft.com/fwlink/?LinkId=787528)를 참조합니다.
  -  해당되는 경우 각 소스 환경이 최신 서비스 팩(SP) 및 롤업(RU)/누적 업데이트(CU) 레벨에 있는지 확인합니다.
  -  해당되는 경우 원본 환경과 Exchange 온라인 간의 SMTP 메일 라우팅 공존을 구성하고 검증합니다.
  -  원본 사서함 크기가 대상 사서함 할당량을 초과하지 않도록 합니다. 원본 플랫폼에 따라 소스 데이터를 대상 사서함 할당량의 85%로 제한해야 할 수도 있습니다.
  -  필요한 경우 클라이언트 측 데이터를 마이그레이션합니다. 여기에는 로컬 주소록, 로컬 PST 파일의 데이터, Outlook 규칙 및 로컬 Outlook 설정이 포함되지만 이에 국한되지는 않습니다.
  -  최종 사용자가 클라이언트 측 마이그레이션 문제를 해결할 수 있도록 지원합니다.

## <a name="migration-to-sharepoint-online"></a>SharePoint Online으로 마이그레이션

FastTrack을 사용하여 SharePoint Online으로 파일을 마이그레이션하도록 선택하면 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다. Microsoft는 마이그레이션 계획, 소스 환경 및 SharePoint 온라인 구성, 데이터 마이그레이션 서비스를 활용하여 파일을 마이그레이션하는 데 도움이 되는 지침을 제공합니다. 마이그레이션 이벤트를 생성하고 예약합니다. 스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다. 마이그레이션 이벤트가 완료되면 적절한 예약 소스 및 적합한 소스 소스의 파일이 SharePoint 온라인으로 마이그레이션될 것으로 예상할 수 있습니다.

## <a name="considerations"></a>고려 사항

  - 모든 마이그레이션은 SharePoint 온라인 할당량을 따릅니다. 자세한 내용은 [<span class="underline">SharePoint 온라인 및 OneDrive for Business: 소프트웨어 경계 및 제한</span>](https://go.microsoft.com/fwlink/?LinkId=698855)을(를) 참조합니다.
  - 전체 마이그레이션 양을 사용 권한이 있는 전체 SharePoint 온라인 스토리지 할당량의 75%로 제한하는 것이 좋습니다(별도로 구입한 추가 스토리지 포함).

## <a name="source-environment-details"></a>소스 환경 세부 정보

Microsoft의 데이터 마이그레이션 서비스는 다음과 같은 소스 환경에서 데이터를 마이그레이션합니다.

  - 파일 공유(SMB 2.0 이상 지원 장치에서 SMB(서버 메시지 블록) 파일 공유).
  - 단일 G 제품군 환경(Google Drive만 해당)
  - Box(Starter, Business, Enterprise)
  - Teams용 Dropbox (표준 및 고급)

다음 표에서는 각 소스 환경에 대한 마이그레이션 세부 정보를 보여 줍니다.

<table>
<thead>
<tr class="header">
<th><strong>원본 환경</strong></th>
<th><strong>마이그레이션 유형</strong></th>
<th><strong>마이그레이트 대상</strong></th>
 <th><strong>마이그레이션되지 않는 사항</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>SMB 2.0 이상을 지원하는 모든 파일 공유 장치</strong></td>
<td>단일 또는 멀티패스</td>
<td><ul>
<li> 문서 </li>
<li> 파일 및 폴더 구조 </li>
<li> 사용자 수준 파일 및 폴더 권한* </li>
<li> 그룹 수준 파일 및 폴더 권한* </li>
<li> 15GB 미만 파일 </li>
<li> 기본 문서 및 폴더 메타데이터:
<ul>
<li> 만든 날짜 </li>
<li> 수정한 날짜 </li>
<li> 만든 사람 </li>
<li> 마지막 수정한 날짜 </li>
</ul></li>
</ul>
* 디렉터리 동기화 구성이 필요합니다. Windows 파일 탐색기에 표시된 NTFS 권한만 마이그레이션됩니다. 파일 공유 장치에서 직접 관리되는 사용 권한은 마이그레이션되지 않습니다. 데이터가 SMB 2.0 장치에 저장된 경우 SMB 프로토콜에 의해 노출된 NTFS 동등 사용 권한이 마이그레이션됩니다.</td>
<td><ul>
<li> 소유권 기록 및 이전 버전 </li>
<li> 콘텐츠에 포함된 URL 변환 </li>
<li> 이전 버전 </li>
<li> Windows 파일 및 폴더 특성(예: 읽기 전용 및 숨김) </li>
<li> Windows가 아닌 NTFS(New Technology File System) 및 NTFS 고급 사용 권한 및 특수 설정: </li>
<li> 명시적 거부 사용 권한(마이그레이션 후 제거됨, 콘텐츠는 병렬 사용 권한 또는 상위 폴더의 사용 권한에 따름) </li>
<li> NTFS 감사 구성 </li>
<li> FCI(파일 분류 인프라)에 의해 제공되는 추가 파일 메타데이터 </li>
<li> 액세스할 수 없거나 손상된 문서 </li>
<li> 숨겨진 공유 </li>
<li> 공유(예: 공유 수준에 부여된 사용 권한) </li>
<li> 현재 SharePoint Online 제한 사항을 초과하는 파일 또는 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">폴더</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>단일 G 제품군 환경(Google Drive만 해당)</strong></td>
<td>단일 또는 멀티패스</td>
<td><ul>
<li> Google 문서, 스프레드시트 및 슬라이드(파일이 동등한 Office 형식으로 변환됨 / 10MB 초과하는 파일 포함) </li>
<li> 파일 및 폴더 구조 </li>
<li> 사용자 수준 폴더 권한 </li>
<li> 그룹 수준 폴더 권한 </li>
<li> 15GB 미만 파일 </li>
<li> 기본 문서 및 폴더 메타데이터:
<ul>
<li> 만든 날짜 </li>
<li> 수정한 날짜 </li>
<li> 만든 사람 </li>
<li> 마지막 수정 날짜 </li>
</ul></li>
<li> 공유 드라이브(폴더 및 파일) </li>
<li> Google Drive 계정이 소유한 공유 콘텐츠를 마이그레이션합니다. </li>
</ul></td>
<td><ul>
<li> 소유권 기록, 이전 버전 및 메모 </li>
<li> 파일 및 폴더 설명, 폴더 색상 </li>
<li> 사용자 수준 파일 권한 </li>
<li> 그룹 수준 파일 권한 </li>
<li> 고급 메타 데이터 </li>
<li> 파일 잠금 특성 </li>
<li> 콘텐츠에 포함된 URL 변환 </li>
<li> 휴지통 항목 </li>
<li> 액세스할 수 없거나 손상된 문서 </li>
<li> 차단되거나 비활성 상태인 사용자 </li>
<li> Google Photos. Forms, Maps 및 기타 연결된 앱 </li>
<li> Google 드로잉 </li>
<li> 조직 외부로 공유된 콘텐츠 </li>
<li> 마이그레이션할 Google Drive 계정에서 소유하지 않은 콘텐츠 </li>
<li> 외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다. 최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.) </li>
<li> 공유 드라이브 구성원 권한(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 공유 드라이브 구성원 자격을 식별합니다. 마이그레이션하기 전에 최종 사용자에게 대상에서 이러한 구성원 자격 설정을 구성하도록 지시합니다.) </li>
<li> 제한된 것으로 표시되거나 복사할 수 없는 파일 </li>
<li> 현재 SharePoint Online 제한 사항을 초과하는 파일 또는 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">폴더</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box(Starter, Business, Enterprise)</strong></td>
<td>단일 또는 멀티패스</td>
<td><ul>
<li> 문서 </li>
<li> 파일 및 폴더 구조 </li>
<li> 사용자 수준 폴더 권한 </li>
<li> 그룹 수준 폴더 권한 </li>
<li> 15GB 미만 파일 </li>
<li> 기본 문서 및 폴더 메타데이터:
<ul>
<li> 만든 날짜 </li>
<li> 수정한 날짜 </li>
<li> 만든 사람 </li>
<li> 마지막 수정 날짜 </li>
</ul></li>
<li> Box 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다. </li>
<li> Box 메모(Word 문서 형식으로 변환) </li>
</ul></td>
<td><ul>
<li> 소유권 기록, 이전 버전 및 메모 </li>
<li> 파일 및 폴더 설명 </li>
<li> 사용자 수준 파일 권한 </li>
<li> 그룹 수준 파일 권한 </li>
<li> Box 태그와 고급 메타데이터 </li>
<li> 파일 잠금 특성 </li>
<li> 콘텐츠에 포함된 URL 변환 </li>
<li> 휴지통 항목 </li>
<li> 액세스할 수 없거나 손상된 문서 </li>
<li> 차단되거나 비활성 상태인 사용자 </li>
<li> Box 앱, 책갈피, 즐겨찾기 및 워크플로 </li>
<li> 마이그레이션된 상자 계정에서 소유하지 않은 콘텐츠입니다. </li>
<li> 외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Box 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다. 최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.) </li>
<li> 현재 SharePoint Online 제한 사항을 초과하는 파일 또는 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">폴더</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Teams용 Dropbox(표준 및 고급)</strong></td>
<td>단일 또는 멀티패스</td>
<td><ul>
<li> 문서 </li>
<li> 파일 및 폴더 구조 </li>
<li> 사용자 수준 폴더 권한 </li>
<li> 그룹 수준 폴더 권한 </li>
<li> 15GB 미만 파일 </li>
<li> 기본 문서 및 폴더 메타데이터:
<ul>
<li> 만든 날짜 </li>
<li> 수정한 날짜 </li>
<li> 만든 사람 </li>
<li> 마지막 수정 날짜 </li>
</ul></li>
<li> 공유 팀 폴더 및 콘텐츠 </li>
<li> Dropbox 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다. </li>
</ul></td>
<td><ul>
<li> 소유권 기록, 이전 버전 및 메모 </li>
<li> 파일 및 폴더 설명 </li>
<li> 사용자 수준 파일 권한 </li>
<li> 그룹 수준 파일 권한 </li>
<li> 고급 메타 데이터 </li>
<li> 파일 잠금 특성 </li>
<li> 콘텐츠에 포함된 URL 변환 </li>
<li> 휴지통 항목 </li>
<li> 액세스할 수 없거나 손상된 문서 </li>
<li> 연결 해제된 Dropbox 폴더 </li>
<li> 삭제되거나 연결이 끊어진 사용자 </li>
<li> Dropbox Paper, Showcases 및 Spaces </li>
<li> Dropbox 앱 및 즐겨찾기(핀/별) </li>
<li> 마이그레이션된 Dropbox 계정이 소유하지 않은 콘텐츠 </li>
<li> 외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>: Dropbox 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다. 최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.) </li>
<li> 현재 SharePoint Online 제한 사항을 초과하는 파일 또는 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">폴더</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>FastTrack 책임

Microsoft의 FastTrack 전문가는 마이그레이션 프로젝트 중에 표준 작업을 수행합니다. 자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.

## <a name="your-responsibilities"></a>귀하의 책임

마이그레이션 프로젝트 중에 표준 작업을 수행합니다. 자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.

또한 SharePoint 온라인 마이그레이션과 관련된 다음 작업도 수행합니다.

  - 모든 SharePoint 팀 사이트를 마이그레이션 이벤트의 대상으로 프로비저닝합니다.

## <a name="migration-to-onedrive-for-business"></a>비즈니스용 OneDrive로 마이그레이션

FastTrack을 사용하여 파일을 비즈니스용 OneDrive로 마이그레이션하도록 선택하면 마이그레이션 안내 및 데이터 마이그레이션 서비스를 제공합니다. Microsoft는 마이그레이션 계획, 소스 환경 및 비즈니스용 OneDrive 구성, 데이터 마이그레이션 서비스를 활용하여 파일을 마이그레이션하는 데 도움이 되는 지침을 제공합니다. 마이그레이션 이벤트를 생성하고 예약합니다. 스케줄에 따라 마이그레이션 이벤트를 시작하고 진행률을 모니터링하며 상태 보고서를 제공합니다. 마이그레이션 이벤트가 완료되면 적절한 소스 환경의 적절한 예약 소스 및 적합한 원본의 파일이 비즈니스용 OneDrive로 마이그레이션될 것으로 예상할 수 있습니다.

## <a name="considerations"></a>고려 사항

  - 모든 마이그레이션에는 비즈니스용 OneDrive 할당량이 적용됩니다. 자세한 내용은 [<span class="underline">SharePoint Online 및 비즈니스용 OneDrive: 소프트웨어 경계 및 제한</span>](https://go.microsoft.com/fwlink/?LinkId=698855)을 참조하시기 바랍니다.
  - 마이그레이션하는 전체 데이터 양을 권한이 부여된 전체 SharePoint 온라인 스토리지 할당량의 75%로 제한하는 것이 좋습니다(별도로 구입한 추가 스토리지 포함).
  - FastTrack은 활성 비즈니스용 OneDrive 드라이브로만 마이그레이션합니다.

## <a name="source-environment-details"></a>소스 환경 세부 정보

Microsoft의 데이터 마이그레이션 서비스는 다음과 같은 소스 환경에서 데이터를 마이그레이션합니다.

  - 파일 공유(SMB 2.0 이상 지원 장치에서 SMB 파일 공유)
  - 단일 G 제품군 환경(Google Drive만 해당)
  - Box(Starter, Business, Enterprise)
  - Teams용 Dropbox (표준 및 고급)

다음 표에서는 각 소스 환경에 대한 마이그레이션 세부 정보를 보여 줍니다.

<table>
<thead>
<tr class="header">
 <th><strong>원본 환경</strong></th>
 <th><strong>마이그레이션 유형</strong></th>
 <th><strong>마이그레이트 대상</strong></th>
 <th><strong>마이그레이션되지 않는 사항</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>SMB 2.0 이상을 지원하는 모든 파일 공유 장치</strong></td>
<td>단일 또는 멀티패스</td>
<td><ul>
<li> 문서 </li>
<li> 파일 및 폴더 구조 </li>
<li> 사용자 수준 파일 및 폴더 권한* </li>
<li> 그룹 수준 파일 및 폴더 권한* </li>
<li> 15GB 미만 파일 </li>
<li> 기본 문서 및 폴더 메타데이터:
<ul>
<li> 만든 날짜 </li>
<li> 수정한 날짜 </li>
<li> 만든 사람 </li>
<li> 마지막 수정한 날짜 </li>
</ul></li>
</ul>
<br>
* 디렉터리 동기화 구성이 필요합니다. Windows 파일 탐색기에 표시된 NTFS 권한만 마이그레이션됩니다. 파일 공유 장치에서 직접 관리되는 사용 권한은 마이그레이션되지 않습니다. 데이터가 SMB 2.0 장치에 저장된 경우 SMB 프로토콜에 의해 노출된 NTFS 동등 사용 권한이 마이그레이션됩니다. </td>
<td><ul>
<li> 소유권 기록 및 이전 버전 </li>
<li> 콘텐츠에 포함된 URL 변환 </li>
<li> 이전 버전 </li>
<li> Windows 파일 및 폴더 특성(예: 읽기 전용 및 숨김) </li>
<li> Windows가 아닌 NTFS(New Technology File System) 및 NTFS 고급 사용 권한 및 특수 설정: </li>
<li> 명시적 거부 사용 권한(마이그레이션 후 제거됨, 콘텐츠는 병렬 사용 권한 또는 상위 폴더의 사용 권한에 따름) </li>
<li> NTFS 감사 구성 </li>
<li> FCI(파일 분류 인프라)에 의해 제공되는 추가 파일 메타데이터 </li>
<li> 액세스할 수 없거나 손상된 문서 </li>
<li> 숨겨진 공유 </li>
<li> 공유(예: 공유 수준에 부여된 사용 권한) </li>
<li> 현재 SharePoint Online 제한 사항을 초과하는 파일 또는 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">폴더</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>단일 G 제품군 환경(Google Drive만 해당)</strong></td>
<td>단일 또는 멀티패스</td>
<td><ul>
<li> Google 문서, 스프레드시트 및 슬라이드(파일이 동등한 Office 형식으로 변환됨 / 10MB 초과하는 파일 포함) </li>
<li> 파일 및 폴더 구조 </li>
<li> 사용자 수준 폴더 권한 </li>
<li> 그룹 수준 폴더 권한 </li>
<li> 15GB 미만 파일 </li>
<li> 기본 문서 및 폴더 메타데이터:
<ul>
<li> 만든 날짜 </li>
<li> 수정한 날짜 </li>
<li> 만든 사람 </li>
<li> 마지막 수정 날짜 </li>
</ul></li>
<li> 공유 드라이브(폴더 및 파일) </li>
<li> Google Drive 계정이 소유한 공유 콘텐츠를 마이그레이션합니다. </li>
</ul></td>
<td><ul>
<li> 소유권 기록, 이전 버전 및 메모 </li>
<li> 파일 및 폴더 설명, 폴더 색상 </li>
<li> 사용자 수준 파일 권한 </li>
<li> 그룹 수준 파일 권한 </li>
<li> 고급 메타 데이터 </li>
<li> 파일 잠금 특성 </li>
<li> 콘텐츠에 포함된 URL 변환 </li>
<li> 휴지통 항목 </li>
<li> 액세스할 수 없거나 손상된 문서 </li>
<li> 차단되거나 비활성 상태인 사용자 </li>
<li> Google Photos. Forms, Maps 및 기타 연결된 앱 </li>
<li> Google 드로잉 </li>
<li> 조직 외부로 공유된 콘텐츠 </li>
<li> 마이그레이션할 Google Drive 계정에서 소유하지 않은 콘텐츠 </li>
<li> 외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다. 최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.) </li>
<li> 공유 드라이브 구성원 권한(<strong>참고</strong>): Google Drive Admin 보고서를 사용하여 공유 드라이브 구성원 자격을 식별합니다. 마이그레이션하기 전에 최종 사용자에게 대상에서 이러한 구성원 자격 설정을 구성하도록 지시합니다.) </li>
<li> 현재 SharePoint Online 제한 사항을 초과하는 파일 또는 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">폴더</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box(Starter, Business, Enterprise)</strong></td>
<td>단일 또는 멀티패스</td>
<td><ul>
<li> 문서 </li>
<li> 파일 및 폴더 구조 </li>
<li> 사용자 수준 폴더 권한 </li>
<li> 그룹 수준 폴더 권한 </li>
<li> 15GB 미만 파일 </li>
<li> 기본 문서 및 폴더 메타데이터:
<ul>
<li> 만든 날짜 </li>
<li> 수정한 날짜 </li>
<li> 만든 사람 </li>
<li> 마지막 수정 날짜 </li>
</ul></li>
<li> Box 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다. </li>
</ul></td>
<td><ul>
<li> 소유권 기록, 이전 버전 및 메모 </li>
<li> 파일 및 폴더 설명 </li>
<li> 사용자 수준 파일 권한 </li>
<li> 그룹 수준 파일 권한 </li>
<li> Box 태그와 고급 메타데이터 </li>
<li> 파일 잠금 특성 </li>
<li> 콘텐츠에 포함된 URL 변환 </li>
<li> 휴지통 항목 </li>
<li> 액세스할 수 없거나 손상된 문서 </li>
<li> 차단되거나 비활성 상태인 사용자 </li>
<li> Box 앱, 책갈피, 즐겨찾기 및 워크플로 </li>
<li> 마이그레이션된 상자 계정에서 소유하지 않은 콘텐츠입니다. </li>
<li> 외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>): Box 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다. 최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.) </li>
<li> 현재 SharePoint Online 제한 사항을 초과하는 파일 또는 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">폴더</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Teams용 Dropbox(표준 및 고급)</strong></td>
<td>단일 또는 멀티패스</td>
<td><ul>
<li> 문서 </li>
<li> 파일 및 폴더 구조 </li>
<li> 사용자 수준 폴더 권한 </li>
<li> 그룹 수준 폴더 권한 </li>
<li> 15GB 미만 파일 </li>
<li> 기본 문서 및 폴더 메타데이터:
<ul>
<li> 만든 날짜 </li>
<li> 수정한 날짜 </li>
<li> 만든 사람 </li>
<li> 마지막 수정 날짜 </li>
</ul></li>
<li> 공유 팀 폴더 및 콘텐츠 </li>
<li> Dropbox 계정이 소유한 공유 콘텐츠가 마이그레이션됩니다. </li>
</ul></td>
<td><ul>
<li> 소유권 기록, 이전 버전 및 메모 </li>
<li> 파일 및 폴더 설명 </li>
<li> 사용자 수준 파일 권한 </li>
<li> 그룹 수준 파일 권한 </li>
<li> 고급 메타 데이터 </li>
<li> 파일 잠금 특성 </li>
<li> 콘텐츠에 포함된 URL 변환 </li>
<li> 휴지통 항목 </li>
<li> 액세스할 수 없거나 손상된 문서 </li>
<li> 연결 해제된 Dropbox 폴더 </li>
<li> 삭제되거나 연결이 끊어진 사용자 </li>
<li> Dropbox Paper, Showcases 및 Spaces </li>
<li> Dropbox 앱 및 즐겨찾기(핀/별) </li>
<li> 마이그레이션된 Dropbox 계정이 소유하지 않은 콘텐츠 </li>
<li> 외부 사용자의 사용 권한 및 기본 메타데이터(<strong>참고</strong>: Dropbox 보고서를 사용하여 외부 사용자와 공유된 콘텐츠를 식별합니다. 최종 사용자에게 마이그레이션 후 외부 사용자와 컨텐츠를 재구성하도록 지시합니다.) </li>
<li> 현재 SharePoint Online 제한 사항을 초과하는 파일 또는 <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">폴더</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>FastTrack 책임

Microsoft의 FastTrack 전문가는 마이그레이션 프로젝트 중에 표준 작업을 수행합니다. 자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.

## <a name="your-responsibilities"></a>귀하의 책임

마이그레이션 프로젝트 중에 표준 작업을 수행합니다. 자세한 내용은 [프로세스 및 기대 사항](process-and-expectations.md)의 데이터 마이그레이션 책임 정보를 참조합니다.

또한 비즈니스용 OneDrive 마이그레이션과 관련된 다음 작업도 수행합니다.

  - 마이그레이션 이벤트의 대상이 되는 비즈니스 사이트를 위해 모든 OneDrive를 프로비저닝합니다.
