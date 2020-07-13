---
title: 데이터 마이그레이션
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack Specialists provide guidance on steps for data migration to Office 365. This is available for all eligible customers with Office 365 services for Exchange Online, OneDrive for Business, and SharePoint Online.
ms.openlocfilehash: 7780af3d5edcdbdf21acba1d421bf379967305fa
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011312"
---
# <a name="data-migration"></a>데이터 마이그레이션

원본 환경에 Office 365로 마이그레이션하려는 데이터가 있을 수 있습니다.

**150~499개 라이선스를 보유한 Office 365 테넌트:** 도구와 문서를 조합하여 지침을 제공하기 때문에 마이그레이션을 부드럽고 효율적으로 수행할 수 있습니다. 

**500개 이상의 라이선스를 보유한 Office 365 테넌트\*:** Exchange Online, SharePoint Online 및 비즈니스용 OneDrive에서 데이터 마이그레이션 서비스를 사용할 수 있습니다. FastTrack 혜택에는 원본 환경 통합 및 데이터 마이그레이션에 대한 지침 제공이 포함됩니다.
  
\*If you purchased or renewed a commercial plan prior to 9/1/2017, 150 seats is the minimum seat requirement throughout your current subscription period in order to receive the migration benefit. For education plans, only paid faculty and staff licenses are eligible for migration services. 
  
> [!NOTE]
> Data migrated through the FastTrack services may be transferred to, stored, and processed anywhere that Microsoft maintains facilities (except as otherwise provided for your particular FastTrack engagement). The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements. 
  
> [!NOTE]
> 예기치 못한 문제(원본 환경에서 읽을 수 없거나 손상된 항목을 포함하되 이에 국한되지 않음)는 일부 항목의 마이그레이션을 차단할 수 있습니다. 
  
> [!NOTE]
> 마이그레이션 지원은 중국어 번체, 중국어 간체(지원 담당자가 만다린어만 사용), 영어, 프랑스어, 독일어, 이탈리아어, 일본어, 포르투갈어(브라질) 및 스페인어로 제공됩니다. 
  
> [!NOTE]
> 통합이 필요한 경우 원본 환경은 해당 응용 프로그램의 수준 이상이어야 합니다. 
  
> [!NOTE]
> 2020년 3월의 새 소식. Microsoft는 고객이 COVID-19 발생에 대응하는 동안에 원격 작업 및 학습을 지원하기 위해 6개월간 [Office 365 E1](https://docs.microsoft.com/microsoftteams/e1-trial-license) 및 [Office 365 G1](https://docs.microsoft.com/microsoftteams/g1-trial-license) 평가판 라이선스를 제공합니다. 예외적으로, FastTrack은 2020년 3월부터 2020년 8월까지 해당 평가판의 라이선스가 500개 이상 있는 테넌트와 학생용 [Office 365 A1](https://www.microsoft.com/microsoft-365/academic/compare-office-365-education-plans?activetab=tab:primaryr1)에 사용할 수 있는 데이터 마이그레이션 서비스를 만듭니다. Microsoft는 예고 없이 언제든지 이 제안을 취소, 변경 또는 일시 중단할 수 있습니다.

다음 표에는 기존 원본 환경에서 요구되는 마이그레이션 조건이 설명되어 있습니다.
  

|**작업**|**원본 환경 요구 조건**|
|:-----|:-----|
|**Exchange Online 마이그레이션**  <br/> | Microsoft migrates any combination of the source environments listed below, each one at a time. We can migrate the onboarded messaging system using the FastTrack Center or if it's passed the FastTrack Center checks. This includes:  <br/>  단일 또는 다중 Exchange 조직이 있는 단일 또는 다중 Active Directory 포리스트. 단, Exchange 2010 기반 하이브리드 이상이 각 조직에서 구현되고 Exchange 메일 시스템은 2003 이상이어야 합니다.  <br/>  단일 IMAP 지원 전자 메일 환경  <br/>  G 제품군 환경(Gmail, 연락처 및 캘린더만) <br/> <br/> **참고** *Exchange Online 온보딩은 마이그레이션 전에 완료되어야 합니다.* <br/> <br/> **참고** *FastTrack은 Office 365 사서함을 활성화하려 할 때만 마이그레이션합니다.* <br/> <br/> **참고** *온-프레미스 Exchange 종속성의 경우 [하이브리드 배포 필수 구성 요소](https://go.microsoft.com/fwlink/?LinkId=787528)를 참조하세요.* <br/><br/> **참고** *여러 원본 메시징 환경(예: 다중 Exchange 조직 또는 다중 Domino 도메인)을 마이그레이션할 때 이러한 마이그레이션이 순차적으로 수행됩니다.*| 
|**SharePoint Online 마이그레이션**  <br/> | 파일 공유(SMB 2.0 이상 지원 장치에서 SMB(서버 메시지 블록) 파일 공유). <br/> 단일 G 제품군 환경(Google Drive만 해당)<br/>  Box(Starter, Business, Enterprise)  <br/> Teams용 Dropbox (표준 및 고급)<br/> |
|**비즈니스용 OneDrive 마이그레이션**  <br/> | 파일 공유(SMB 2.0 이상 지원 장치에서 SMB 파일 공유)  <br/>  단일 G 제품군 환경(Google Drive만 해당)  <br/>  Box(Starter, Business, Enterprise) <br/> Teams용 Dropbox (표준 및 고급)<br/><br/> **참고** *FastTrack은 Office 365 드라이브를 활성화하려 할 때만 마이그레이션합니다.*|
   
## <a name="migration-to-exchange-online"></a>Exchange Online으로 마이그레이션
''
### <a name="enable-to-migrate"></a>마이그레이션할 수 있도록 설정
  
Microsoft를 통해 전자 메일을 마이그레이션하면 마이그레이션 시 Exchange Online 및 원본 환경을 사용할 수 있는 참고 자료가 제공됩니다. 원본 환경에 따라 다양한 사용 단계를 수행할 수 있습니다. 도구 및 문서의 조합을 사용하거나 적용이 가능하고 적합한 구성 작업을 수행할 수 있는 참고 자료를 제공합니다. 적용 가능한 매개 변수에 따라, 사서함을 마이그레이션하고, 작업을 모니터링하고, 상태 보고서를 제공합니다.
''Microsoft에 마이그레이션 활동을 수행하기 위해 메일 시스템에 대한 적절한 액세스 및 권한이 필요할 수 있습니다.
  
### <a name="migration-policy-and-steps"></a>마이그레이션 정책 및 단계
  
> [!NOTE]
> 마이그레이션 시간 슬롯을 마이그레이션 일괄 처리라고도 합니다.

#### <a name="commercial-and-uk-government"></a>상업용 및 영국 정부

Migrations are done on a standardized prescheduled 24 hours a day, seven (7) business days a week (24x7) basis in predefined migration time slots. There are three migration batches per migration day.

#### <a name="us-governmentdod"></a>미국 정부/DOD

Migrations are done on standardized prescheduled 24 hours a day, five (5) business days a week (24x5) basis in predefined migration time slots. There are three migration batches per migration day. There are five migration days in a week from Monday 2:00AM Coordinated Universal Time (UTC) to Friday midnight UTC. This means that the last scheduled migration is Friday 8:00 PM UTC.
    
 ### <a name="end-state"></a>최종 상태
  
마이그레이션 일괄 처리 후의 예상 최종 상태는 다음과 같습니다.
- 원본 환경에 있는 적절하게 예약되고 적합한 원본 사서함이 Office 365로 마이그레이션됩니다. 
- Microsoft는 마이그레이션 일괄 처리에 대한 마이그레이션 사후 보고서를 제공합니다.
    
모든 마이그레이션이 완료된 후에 예상되는 최종 상태는 다음과 같습니다.
- 다음 표에 정의된 적합한 원본 사서함의 데이터가 Office 365로 마이그레이션됩니다.
- 마이그레이션할 데이터 형식은 아래 표에 설명된 대로 원본 환경에 따라 다릅니다.
    
> [!NOTE]
> All source environments need to be on the latest service packs (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment at the end of the Enable phase. Data migration services are subject to external factors beyond Microsoft's control, like changes to third-party application programming interfaces (APIs), which could result in changes to, delays in, or suspension of these services. For the duration of the FastTrack services, data you make available to Microsoft is accessible from and stored anywhere that Microsoft and its suppliers maintain facilities. 
  
|||||
|:-----|:-----|:-----|:-----|
|**원본 환경**|**마이그레이션 유형**|**원본 사서함에서 마이그레이션되는 항목**|**마이그레이션되지 않는 항목**|
|**Exchange 2003 이상**|단독형| 전자 메일 <br/> 사서함 규칙 <br/> 위임 <br/> 사서함 연락처 <br/> 일정 <br/> 작업 <br/> 권한 관리 전자 메일 <br/> 암호화된 전자 메일| 공용 폴더 <br/> 개인 연락처 <br/> 메일을 사용하는 사용자 <br/> 차단되거나 비활성 상태인 사용자 <br/> 서명 <br/> 사서함 휴지통 <br/>  메시지 크기 제한을 초과하는 모든 전자 메일 <br/> 보관 데이터 <br/> 손상된 항목 <br/>  비활성 사서함 |
|**Exchange 2003 및 Exchange 2007**|미리 구성된| 전자 메일 <br/> 사서함 규칙 <br/> 위임 <br/> 사서함 연락처 <br/> 일정 <br/> 작업 <br/> 권한 관리 전자 메일 <br/> 암호화된 전자 메일| 공용 폴더 <br/> 개인 연락처 <br/> 메일을 사용하는 사용자 <br/> 차단되거나 비활성 상태인 사용자 <br/> 서명 <br/> 사서함 휴지통 <br/> 메시지 크기 제한을 초과하는 모든 전자 메일 <br/> 보관 데이터 <br/> 손상된 항목 <br/> 비활성 사서함 |
|**Exchange 2010, Exchange 2013, Exchange 2016 및 Exchange 2019** <br/><br/> **참고** *온-프레미스 Exchange 종속성의 경우 [하이브리드 배포 필수 구성 요소](https://go.microsoft.com/fwlink/?LinkId=787528)를 참조하세요.*           |하이브리드 배포를 사용하는 마이그레이션| 전자 메일 <br/> 사서함 규칙 <br/> 위임 <br/> 사서함 연락처 <br/> 일정 <br/> Tasks <br/> 서명 <br/> 사용자 사서함과 함께 마이그레이션된 개인 보관 파일 <br/> 복구 가능한 항목 <br/> 권한 관리 전자 메일 <br/> 암호화된 전자 메일| 공용 폴더 <br/> 메시지 크기 제한을 초과하는 모든 전자 메일 <br/> 저널링 보관 또는 모든 타사 보관 솔루션 <br/> 차단되거나 비활성 상태인 사용자 <br/> PST(Personal Storage Table) 파일의 보관 데이터 <br/> 손상된 항목 <br/> 비활성 사서함 |
|**G 제품군 환경(Gmail, 연락처 및 캘린더만)** <br/> <br/> **참고** *G Suite 환경에서 확장 기능을 사용하려면 Google API 및 Google Admin SDK가 있어야 합니다.* <br/>          |단독형 또는 미리 구성| 전자 메일 <br/> 사서함 연락처\*  <br/> 일정 <br/> 레이블 <br/> \*연락처당 최대 3개의 전자 메일 주소가 마이그레이션됩니다.| 규칙 <br/> 위임 <br/> 서명 <br/> 작업 <br/> 메시지 크기 제한을 초과하는 모든 전자 메일 또는 첨부 파일 <br/> 차단되거나 비활성 상태인 사용자 <br/> PST 파일 또는 모든 타사 보관 솔루션(예: Google Vault)의 보관 데이터 <br/> 권한 관리 또는 암호화된 전자 메일 <br/> 손상된 항목 <br/> Google Hangouts\*\* <br/> Google Groups <br/> 리소스 사서함 <br/> 비활성 사서함 <br/> 휴가 설정 및 자동 회신 설정 <br/> 공유 일정, 클라우드 첨부 파일, Google Hangout 링크, 이벤트 색상 <br/>\*\*레이블로 저장된 Hangout 대화가 마이그레이션됩니다. |
|**IMAP4 원본(Domino, GroupWise 및 Zimbra 등)** |기본 IMAP4 도구를 사용한 마이그레이션| 전자 메일 | 규칙 <br/> 위임 <br/> 메일 그룹 <br/> 외부 연락처 <br/> 메일을 사용하는 사용자 <br/> 차단되거나 비활성 상태인 사용자 <br/> 사서함 연락처 <br/> 일정 <br/> 서명 <br/> 작업 <br/> 메시지 크기 제한을 초과하는 모든 전자 메일 <br/> 보관 데이터 <br/> 암호화된 전자 메일 <br/> 손상된 항목 <br/> 비활성 사서함 |
   
> [!NOTE]
> If distribution lists (MailEnabledGroup objects) and external contacts (MailEnabledContact objects) are in the on-premises Active Directory, they can be synchronized using Azure AD Connect. However, they aren't a part of mailbox data migration. For more information, see the **Identity integration** example in [Core](O365-onboarding-and-migration.md#core). 
  
FastTrack Specialists는 마이그레이션 도중 다음을 수행합니다.
- 사서함 마이그레이션 예약에 대한 표준 템플릿을 제공합니다.
- FastTrack 전문가에게 필요한 권한 정보를 제공합니다. 
- 미리 결정된 형식으로 미리 결정된 사서함 마이그레이션 일정을 수집합니다.
- 사서함을 실패한 마이그레이션으로 보고하기 전에 마이그레이션 일괄 처리에서 최대 2번까지 단일 사서함 마이그레이션을 시도합니다.
- Exchange 및 IMAP4 기반 원본 환경에서는 사용자 사서함 저장 용량 제한의 85%까지 사서함 콘텐츠를 마이그레이션합니다. 예를 들어 사서함 저장 용량 제한이 50GB면 Microsoft는 저장 용량 제한 50GB의 85%까지 마이그레이션합니다. 
- 단독형 마이그레이션을 사용 중인 경우가 아니면 SMTP 메일 라우팅이 원본 메시징 환경과 Office 365 Exchange Online 간에 공존하도록 설정합니다.
- 사후 마이그레이션 보고서를 제공합니다.
- Provide post-migration assistance for critical issues. The following issues are considered critical:
  - 마이그레이션 중에 데이터가 손실되었습니다.
  - 마이그레이션 중에 원본 환경을 사용할 수 없습니다.
  - 원본 환경에서 마이그레이션 작업에 문제가 발생했습니다.
    
마이그레이션 도중 다음을 수행합니다.
- FastTrack 센터를 사용하여 Exchange Online 온보딩을 완료하거나 필요한 검사를 통과합니다.
- 최종 사용자와의 모든 통신을 처리합니다.  
- Office 365 지침에 따라 적절한 수준의 클라이언트 소프트웨어를 설치합니다. 자세한 내용은 [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)를 참조하세요. 
- 해당하는 경우 원본 메시징 환경과 Office 365 Exchange Online 간의 SMTP 메일 라우팅 공존에 대한 유효성을 검사합니다.
- 정의된 방법에 대한 일정과 각 마이그레이션 이벤트에 대해 마이그레이션할 특정 사서함 목록을 제공합니다.
- 마이그레이션 일괄 처리가 시작되기 24시간 전까지 일정에서 사서함을 삭제합니다. 
- 다음 표에 나열된 대로 24시간 내에 대상 평균 사서함 수를 예약합니다.
    
|||
|:-----|:-----|
|**마이그레이션에 적합한 사서함 수** <br/> |**24시간 동안 평균 최소 사서함 수** <br/> |
|150-1000  <br/> |전체의 25%  <br/> |
|1001-5000  <br/> |전체의 20%  <br/> |
|5001-10000  <br/> |전체의 15%  <br/> |
|\>10000  <br/> |1500  <br/> |
   
   > [!NOTE]
   > These numbers are based on best practice. However, the number of mailboxes that migrate per day will vary based on environment, readiness, and business constraints. Microsoft can't guarantee the speed of mailbox migration. 
  
- 마이그레이션 일괄 처리에 최소 35개의 사서함을 예약합니다. 
- 마이그레이션 전 오류를 수정합니다(해당하는 경우).  
- 마이그레이션 작업을 수행할 수 있도록 FastTrack 전문가에게 원본 환경에 대한 액세스 및 사용 권한을 제공합니다. 
- 마이그레이션 작업을 수행할 수 있도록 Office 365에서 사용이 허가된 관리 계정을 조달 및/또는 제공합니다(적절한 수준으로). 
- 클라이언트 쪽 마이그레이션 문제를 지원하고 필요한 경우 사후 마이그레이션 작업을 실행합니다. 
- Migrate client-side data if desired. This includes, but is not limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.   
- 대상 Office 365 사서함 제한의 85% 미만으로 사서함 크기를 줄입니다(해당하는 경우).   
- 사후 마이그레이션 보고서에 나열된 작업(예: 이동하지 않은 사서함)을 처리합니다.  
- 사후 마이그레이션 오류를 수정하고 사서함을 다시 예약합니다(해당하는 경우).   
- Engage in post-migration assistance for critical issues. The following issues are considered critical:
  - 마이그레이션 중에 데이터가 손실되었습니다.
  - 마이그레이션 중에 원본 환경을 사용할 수 없습니다.
  - 원본 환경에서 마이그레이션 작업에 문제가 발생했습니다.
    
You need to follow the standard migration process and engage with Microsoft appropriately. This includes providing access and permissions to source and Office 365 environments, providing migration schedules, correcting any causes for migration errors, and so on. You also need to engage with end users for communications, mailbox migration schedule, and handling end user migration-related issues.
  
> [!NOTE]
> Migrations only use accounts that adhere to security requirements defined during onboarding. If you don't use such accounts, you may experience migration delays. 
  
## <a name="migration-to-sharepoint-online"></a>SharePoint Online으로 마이그레이션

### <a name="enable-to-migrate"></a>마이그레이션할 수 있도록 설정
  
If you use Microsoft to migrate your data, we provide guidance to enable both SharePoint Online and the source environment for migration. Depending on the source, we may perform various Enable steps. We provide guidance for you by using a combination of tools and documentation and by performing configuration tasks where applicable and feasible.
  
Microsoft에 특정 활동을 수행하기 위한 적절한 액세스 및 사용 권한을 제공해야 합니다.
  
### <a name="migration-policy-and-steps"></a>마이그레이션 정책 및 단계
  
> [!NOTE]
> 마이그레이션 시간 슬롯을 마이그레이션 일괄 처리라고도 합니다.

#### <a name="commercial-and-uk-government"></a>상업용 및 영국 정부

Migrations are done on a standardized prescheduled 24 hours a day, seven (7) business days a week (24x7) basis in predefined migration time slots. There are three migration batches per migration day.

#### <a name="us-governmentdod"></a>미국 정부/DOD

Migrations are done on standardized prescheduled 24 hours a day, five (5) business days a week (24x5) basis in predefined migration time slots. There are three migration batches per migration day. There are five migration days in a week from Monday 2:00AM Coordinated Universal Time (UTC) to Friday midnight UTC. This means that the last scheduled migration is Friday 8:00 PM UTC.

- 모든 마이그레이션은 [SharePoint Online 및 비즈니스용 OneDrive 소프트웨어 경계 및 제한](https://go.microsoft.com/fwlink/?LinkID=616612)에 설명된 SharePoint Online 할당량에 따라 좌우됩니다.   
- 마이그레이션된 데이터의 전체 크기는 전체의 75%에 바인딩됩니다 SharePoint Online 저장 용량 할당량을 별도로 구입한 있습니다 추가 저장소 등 제공 되는.
    
 ### <a name="end-state"></a>최종 상태
  
마이그레이션 일괄 처리 후의 예상 최종 상태는 다음과 같습니다. 
- 원본 환경에 있는 적절하게 예약되고 적합한 원본 사서함이 Office 365로 마이그레이션됩니다.   
- Microsoft는 마이그레이션 일괄 처리에 대한 마이그레이션 사후 보고서를 제공합니다.
    
모든 마이그레이션이 완료된 후에 예상되는 최종 상태는 다음과 같습니다. 
- 다음 표에 정의된 적합한 원본의 데이터가 Office 365로 마이그레이션됩니다.  
- 마이그레이션할 데이터 형식은 아래 표에 설명된 대로 원본 환경에 따라 다릅니다.
    
|||||
|:-----|:-----|:-----|:-----|
|**원본 환경** <br/> |**마이그레이션 유형** <br/> |**마이그레이션되는 항목** <br/> |**마이그레이션되지 않는 항목** <br/> |
|**SMB 2.0 이상을 지원하는 모든 파일 공유 장치**  <br/> |단일 또는 멀티패스  <br/> | 문서  <br/>  파일 및 폴더 구조  <br/>  사용자 수준 파일 및 폴더 권한\*  <br/>  그룹 수준 파일 및 폴더 권한\*  <br/>  15GB 미만 파일  <br/>  기본 문서 및 폴더 메타데이터:  <br/>  만든 날짜  <br/>  수정한 날짜  <br/>  만든 사람  <br/>  마지막 수정 날짜  <br/><br/> \**디렉터리 동기화 구성이 필요합니다. Windows 파일 탐색기에 표시된 NTFS 권한만 마이그레이션됩니다. 파일 공유 장치에서 직접 관리되는 사용 권한은 마이그레이션되지 않습니다. 데이터가 SMB 2.0 장치에 저장된 경우 SMB 프로토콜에 의해 노출된 NTFS 동등 사용 권한이 마이그레이션됩니다.* <br/> | 소유권 기록 및 이전 버전  <br/>  콘텐츠에 포함된 URL 변환  <br/>  이전 버전  <br/>  Windows 파일 및 폴더 특성(예: 읽기 전용 및 숨김)  <br/>  Windows가 아닌 NTFS(New Technology File System) 및 NTFS 고급 사용 권한 및 특수 설정:  <br/>  명시적 거부 사용 권한(마이그레이션 후 제거됨, 콘텐츠는 병렬 사용 권한 또는 상위 폴더의 사용 권한에 따름)  <br/>  NTFS 감사 구성  <br/>  FCI(파일 분류 인프라)에 의해 제공되는 추가 파일 메타데이터  <br/>  액세스할 수 없거나 손상된 문서  <br/>  숨겨진 공유  <br/>  공유(예: 공유 수준에 부여된 사용 권한)  <br/>  현재 [SharePoint Online 제한 사항을 초과하는 파일 또는 폴더](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**단일 G 제품군 환경(Google Drive만 해당)**  <br/> |단일 또는 멀티패스  <br/> | <br/>  Google 문서, 스프레드시트 및 슬라이드(파일이 동등한 Office 형식으로 변환됨 / 10MB 초과하는 파일 포함) <br/>  파일 및 폴더 구조  <br/>  사용자 수준 폴더 권한  <br/>  그룹 수준 폴더 권한 <br/>  15GB 미만 파일  <br/> 기본 문서 및 폴더 메타데이터: <br/> 만든 날짜  <br/>  수정한 날짜  <br/>  만든 사람  <br/>  마지막 수정 날짜  <br/> 공유 드라이브(폴더 및 파일) <br/>  마이그레이션되는 Google Drive 계정 소유의 공유 콘텐츠(사용자 또는 그룹과 명시적으로 공유하는 경우)\*  <br/><br/> \**Google Drive 관리자를 사용하여 외부 계정을 식별합니다. 최종 사용자에게 마이그레이션 후 콘텐츠를 다시 공유하도록 지시합니다.* <br/> | 소유권 기록, 이전 버전 및 메모 <br/>  파일 및 폴더 설명, 폴더 색상  <br/>  사용자 수준 파일 권한  <br/>  그룹 수준 파일 권한  <br/>  고급 메타 데이터  <br/>  파일 잠금 특성  <br/>  콘텐츠에 포함된 URL 변환  <br/>  휴지통 항목  <br/>  액세스할 수 없거나 손상된 문서  <br/>  차단되거나 비활성 상태인 사용자  <br/>  Google Photos. Forms, Maps 및 기타 연결된 앱  <br/>  Google 드로잉  <br/>  조직 외부로 공유된 콘텐츠  <br/> 마이그레이션할 Google Drive 계정에서 소유하지 않은 콘텐츠 <br/>외부 사용자의 사용 권한 및 기본 메타 데이터  <br/> 공유 드라이브 구성원 권한\* <br/> 현재 [SharePoint Online 제한 사항](https://go.microsoft.com/fwlink/?linkid=846724)을 초과하는 파일 또는 폴더 <br/> <br/> \**Google Drive 관리자를 사용하여 외부 계정을 식별합니다. 최종 사용자에게 마이그레이션 후 콘텐츠를 다시 공유하도록 지시합니다.* <br/>|
|**Box(Starter, Business, Enterprise)**  <br/> |단일 또는 멀티패스  <br/> | 문서  <br/>  파일 및 폴더 구조  <br/>  사용자 수준 폴더 권한  <br/>  그룹 수준 폴더 권한  <br/>  15GB 미만 파일  <br/>  기본 문서 및 폴더 메타데이터:  <br/>  만든 날짜  <br/>  수정한 날짜  <br/>  만든 사람  <br/>  마지막 수정한 날짜  <br/>  마이그레이션되는 Box 계정 소유의 공유 콘텐츠(사용자 또는 그룹과 명시적으로 공유하는 경우)\*  <br/><br/> \**Box 보고서를 사용하여 외부 계정을 식별합니다. 최종 사용자에게 마이그레이션 후 콘텐츠를 다시 공유하도록 지시합니다.* <br/> | 소유권 기록, 이전 버전 및 메모 <br/>  사용자 수준 파일 권한  <br/>  그룹 수준 파일 권한  <br/>  파일 및 폴더 설명  <br/>  Box 태그와 고급 메타데이터  <br/>  파일 잠금 특성  <br/>  콘텐츠에 포함된 URL 변환  <br/>  휴지통 항목  <br/>  액세스할 수 없거나 손상된 문서  <br/>  차단되거나 비활성 상태인 사용자  <br/>  Box 노트(변환 없이 마이그레이션 시 작동하지 않음)  <br/>  Box 앱, 책갈피, 즐겨찾기 및 워크플로  <br/>  마이그레이션된 Box 계정이 소유하지 않은 콘텐츠(공유 폴더)  <br/>  외부 사용자의 사용 권한 및 기본 메타데이터\*  <br/>  현재 [SharePoint Online 제한 사항을 초과하는 파일 또는 폴더](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/>\**Google Drive 관리자를 사용하여 공유 드라이브 구성원 자격을 식별합니다. 마이그레이션 전에 대상에 대한 구성원 자격 설정을 구성하도록 최종 사용자에게 지시합니다.* |
|**Teams용 Dropbox(표준 및 고급)**  <br/> |단일 또는 멀티패스  <br/> | 문서  <br/>  파일 및 폴더 구조  <br/>  사용자 수준 폴더 권한  <br/>  그룹 수준 폴더 권한  <br/>  15GB 미만 파일  <br/>  기본 문서 및 폴더 메타데이터:  <br/>  만든 날짜  <br/>  수정한 날짜  <br/>  만든 사람  <br/>  마지막 수정 날짜  <br/> 공유 팀 폴더 및 콘텐츠 <br/>  마이그레이션되는 Dropbox 계정 소유의 공유 콘텐츠(사용자 또는 그룹과 명시적으로 공유하는 경우)\*  <br/> <br/> \**Dropbox 보고서를 사용하여 외부 계정을 식별합니다. 최종 사용자에게 마이그레이션 후 콘텐츠를 다시 공유하도록 지시합니다.* <br/> | 소유권 기록, 이전 버전 및 메모 <br/>  파일 및 폴더 설명 <br/>  사용자 수준 파일 권한  <br/>  그룹 수준 파일 권한    <br/> 고급 메타 데이터  <br/>  파일 잠금 특성  <br/>  콘텐츠에 포함된 URL 변환  <br/>  휴지통 항목  <br/>  액세스할 수 없거나 손상된 문서  <br/>  연결 해제된 Dropbox 폴더 <br/>  삭제되거나 연결이 끊어진 사용자 <br/>  Dropbox Paper, Showcases 및 Spaces  <br/> Dropbox 앱 및 즐겨찾기(핀/별) <br/> 마이그레이션된 Dropbox 계정이 소유하지 않은 콘텐츠  <br/>  외부 사용자의 사용 권한 및 기본 메타데이터\*  <br/>  현재 [SharePoint Online 제한 사항을 초과하는 파일 또는 폴더](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/> \**Dropbox 보고서를 사용하여 외부 계정을 식별합니다. 최종 사용자에게 마이그레이션 후 콘텐츠를 다시 공유하도록 지시합니다.* <br/> |
   
FastTrack Specialists는 마이그레이션 도중 다음을 수행합니다. 
- 선택한 마이그레이션 시나리오에 대한 프로세스 및 접근 방식을 다루는 마이그레이션 연습 워크숍을 실시합니다.
- 시나리오에 따라 적절하게 평가 및 마이그레이션 도구의 필수 구성 요소를 제공합니다.   
- 평가 및 마이그레이션 목적으로 원본 및 대상 환경에 마이그레이션 팀이 액세스하기 위한 필수 구성 요소를 제공합니다. 
- 평가 대상/원본 환경에 대한 평가를 수행하기 위한 평가 도구를 제공하거나 네이티브 원본 플랫폼 기능을 사용하여 평가 보고서를 만드는 방법에 대한 지침을 제공합니다.   
- 평가 및 마이그레이션 도구의 배포와 실행을 지원합니다(해당되는 경우).   
- 콘텐츠 마이그레이션을 준비할 때 마이그레이션 인프라를 구성합니다(해당되는 경우).    
- 제한된 테스트 마이그레이션을 수행하여 마이그레이션 인프라 및 필수 구성 요소를 확인합니다.   
- 기본 형태의 대상 SharePoint Online 사이트를 마이그레이션의 일부로 프로비전합니다.    
- 빠른 마이그레이션 전에 파일럿 마이그레이션을 1회 수행합니다.   
- 선택한 시나리오의 마이그레이션 일정에 대한 지침을 제공합니다. 
- 고객이 제공하고 FastTrack 리소스가 유효성을 검사한 마이그레이션 일정에 따라 콘텐츠의 빠른 마이그레이션 과정을 진행합니다.   
- 각 마이그레이션 기간 후에 마이그레이션 결과를 제공합니다.   
- 빠른 마이그레이션 문제 분류에 참여하고 가능한 수정 옵션에 대한 지침을 제공합니다.   
- 빠른 각 마이그레이션 기간에 대한 최종 마이그레이션 보고서를 제공합니다.   
- 마이그레이션이 완료되고 최대 5일 내에 진행되는 사용자 승인 테스트 동안 마이그레이션 후 지원을 제공합니다.
    
마이그레이션 도중 다음을 수행합니다. 
- Provide project resources recommended for assessment and migration activities. These include: 
  - 프로젝트 관리 
  - UAT(사용자 승인 테스트)  
  - 원본 및 대상 콘텐츠 플랫폼을 담당하는 관리자  
- 평가 및 마이그레이션 작업을 위한 인프라 필수 구성 요소를 제공합니다(필요한 경우).  
- 마이그레이션 작업을 수행할 수 있도록 FastTrack 전문가에게 원본 및 대상 환경에 대한 액세스 및 사용 권한을 제공합니다(필요한 경우).
    > [!NOTE]
    > Migrations only use accounts that adhere to security requirements defined during onboarding. If you don't use such accounts, you may experience migration delays. 
- 필수 구성 요소를 제공하고 평가 및 마이그레이션을 지원하는 데 필요한 작업을 수행합니다.   
- FastTrack에서 제공하는 평가 도구를 설치하고 평가 데이터 수집 작업을 완료합니다(해당되는 경우).   
- FastTrack에서 제공하는 마이그레이션 소프트웨어를 온-프레미스에서 설치합니다(해당되는 경우).   
- FastTrack에서 제공하는 수정 보고서에 대략적으로 설명된 수정 작업을 완료합니다(해당되는 경우).  
- FastTrack 템플릿 및 지침을 사용하여 마이그레이션 일정을 제공합니다.   
- 마이그레이션 품질 보증 및 사용자 승인 테스트를 수행합니다.   
- 마이그레이션 후 마이그레이션 수정을 수행합니다(해당하는 경우).
- 변경 관리 및 최종 사용자 의사 소통을 계획하고 구현합니다(해당되는 경우).   
- 평가 및 마이그레이션 활동을 성공적으로 완료하는 데 필요한 원본 시스템 및 장치에 대한 변경 사항을 관리하고 구성합니다.
- 정의된 방법에 대한 일정과 각 마이그레이션 이벤트에 대해 마이그레이션하는 데 필요한 특정 사용자 데이터 목록을 최소 3일 전에 제공합니다.
- 마이그레이션 일괄 처리가 시작되기 24시간 전까지 일정에서 사용자 데이터를 삭제합니다. 이것은 최종 마이그레이션 일괄 처리와 일치해야 합니다.
> [!NOTE]
> Microsoft는 파일 마이그레이션의 속도를 보장하지 않습니다.
    
## <a name="migration-to-onedrive-for-business"></a>비즈니스용 OneDrive로 마이그레이션

 ### <a name="enable-to-migrate"></a>마이그레이션할 수 있도록 설정
  
If you use Microsoft to migrate your data, we provide guidance to enable both OneDrive for Business and the source environment for migration. Depending on the source, we may perform various Enable steps. We help you with some activities by using a combination of tools, documentation, and guidance, and by performing configuration tasks where applicable and feasible.
  
You may need to provide appropriate access and permissions to Microsoft to perform some activities. If you don't provide access and/or permissions, you need to perform certain defined tasks yourself with guidance from Microsoft. 
  
### <a name="migration-policy-and-steps"></a>마이그레이션 정책 및 단계
  
> [!NOTE]
> 마이그레이션 시간 슬롯을 마이그레이션 일괄 처리라고도 합니다.

#### <a name="commercial-and-uk-government"></a>상업용 및 영국 정부

Migrations are done on a standardized prescheduled 24 hours a day, seven (7) business days a week (24x7) basis in predefined migration time slots. There are three migration batches per migration day.

#### <a name="us-governmentdod"></a>미국 정부/DOD

Migrations are done on standardized prescheduled 24 hours a day, five (5) business days a week (24x5) basis in predefined migration time slots. There are three migration batches per migration day. There are five migration days in a week from Monday 2:00AM Coordinated Universal Time (UTC) to Friday midnight UTC. This means that the last scheduled migration is Friday 8:00 PM UTC.
    
- 모든 마이그레이션에는 원본 환경에 대하여 적합한 액세스 및 사용 권한이 필요합니다.   
- 모든 마이그레이션은 앞으로 비즈니스용 OneDrive 에 설명 된 할당량 [SharePoint Online 및 비즈니스를 위한 OneDrive: 소프트웨어 경계 및 제한](https://go.microsoft.com/fwlink/?LinkId=698855).
    
 ### <a name="end-state"></a>최종 상태
  
마이그레이션 일괄 처리 후의 예상 최종 상태는 다음과 같습니다.  
- 원본 환경에 있는 적합하게 예약된 원본의 데이터가 비즈니스용 OneDrive로 마이그레이션됩니다.  
- Microsoft는 마이그레이션 일괄 처리에 대한 마이그레이션 사후 보고서를 제공합니다.
    
모든 마이그레이션이 완료된 후에 예상되는 최종 상태는 다음과 같습니다.
- 다음 표에 정의된 적합한 원본의 데이터가 Office 365로 마이그레이션됩니다.  
- 마이그레이션할 데이터 형식은 아래 표에 설명된 대로 원본 환경에 따라 다릅니다.
    
|||||
|:-----|:-----|:-----|:-----|
|**원본 환경**|**마이그레이션 유형**|**마이그레이션되는 항목**|**마이그레이션되지 않는 항목**|
|**SMB 2.0 이상을 지원하는 모든 파일 공유 장치**  <br/> |단일 또는 멀티패스  <br/> | 문서  <br/>  파일 및 폴더 구조  <br/>  사용자 수준 파일 및 폴더 권한\*  <br/>  그룹 수준 파일 및 폴더 권한\*  <br/>  15GB 미만 파일  <br/>  기본 문서 및 폴더 메타데이터:  <br/>  만든 날짜  <br/>  수정한 날짜  <br/>  만든 사람  <br/>  마지막 수정 날짜  <br/> <br/>\**디렉터리 동기화 구성이 필요합니다. Windows 파일 탐색기에 표시된 NTFS 권한만 마이그레이션됩니다. 파일 공유 장치에서 직접 관리되는 사용 권한은 마이그레이션되지 않습니다. 데이터가 SMB 2.0 장치에 저장된 경우 SMB 프로토콜에 의해 노출된 NTFS 동등 사용 권한이 마이그레이션됩니다.* <br/> | 소유권 기록 및 이전 버전  <br/>  콘텐츠에 포함된 URL 변환  <br/>  이전 버전  <br/>  Windows 파일 및 폴더 특성(예: 읽기 전용 및 숨김)  <br/>  Windows가 아닌 NTFS(New Technology File System) 및 NTFS 고급 사용 권한 및 특수 설정:  <br/>  명시적 거부 사용 권한(마이그레이션 후 제거됨, 콘텐츠는 병렬 사용 권한 또는 상위 폴더의 사용 권한에 따름)  <br/>  NTFS 감사 구성  <br/>  FCI에서 제공하는 추가 파일 메타데이터  <br/>  액세스할 수 없거나 손상된 문서  <br/>  숨겨진 공유  <br/>  공유(예: 공유 수준에 부여된 사용 권한)  <br/>  현재 [SharePoint Online 제한 사항을 초과하는 파일 또는 폴더](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**단일 G 제품군 환경(Google Drive만 해당)**  <br/> |단일 또는 멀티패스  <br/> | Google 문서, 스프레드시트 및 슬라이드(파일이 동등한 Office 형식으로 변환됨 / 10MB 초과하는 파일 포함)  <br/>  파일 및 폴더 구조  <br/>  사용자 수준 폴더 권한  <br/>  그룹 수준 폴더 권한  <br/>  15GB 미만 파일  <br/>  기본 문서 및 폴더 메타데이터:  <br/>  만든 날짜  <br/>  수정한 날짜  <br/>  만든 사람  <br/>  마지막 수정 날짜  <br/> 공유 드라이브(폴더 및 파일) <br/> 마이그레이션되는 Google Drive 계정 소유의 공유 콘텐츠(사용자 또는 그룹과 명시적으로 공유하는 경우)\* <br/> <br/>\**Google Drive 관리자를 사용하여 외부 계정을 식별합니다. 최종 사용자에게 마이그레이션 후 콘텐츠를 다시 공유하도록 지시합니다.* <br/> | 소유권 기록, 이전 버전 및 메모  <br/>  파일 및 폴더 설명, 폴더 색상  <br/>   사용자 수준 파일 권한  <br/>  그룹 수준 파일 권한  <br/> 고급 메타 데이터 <br/>  파일 잠금 특성 <br/> 콘텐츠에 포함된 URL 변환  <br/> 휴지통 항목 <br/> 액세스할 수 없거나 손상된 문서 <br/> 차단되거나 비활성 상태인 사용자 <br/> Google Photos <br/> Forms, Maps 및 기타 연결된 앱 <br/> Google 드로잉 <br/> 조직 외부로 공유된 콘텐츠 <br/> 마이그레이션할 Google Drive 계정에서 소유하지 않은 콘텐츠 <br/> 외부 사용자의 사용 권한 및 기본 메타 데이터<br/> 공유 드라이브 구성원 권한\*<br/> 현재 [SharePoint Online 제한 사항](https://go.microsoft.com/fwlink/?linkid=846724)을 초과하는 파일 또는 폴더 <br/><br/> \**Google Drive 관리자를 사용하여 공유 드라이브 구성원 자격을 식별합니다. 마이그레이션 전에 대상에 대한 구성원 자격 설정을 구성하도록 최종 사용자에게 지시합니다.* <br/> |
|**Box(Starter, Business, Enterprise)**  <br/> |단일 또는 멀티패스  <br/> | 문서  <br/>  파일 및 폴더 구조  <br/>  사용자 수준 폴더 권한  <br/>  그룹 수준 폴더 권한  <br/>  15GB 미만 파일  <br/>  기본 문서 및 폴더 메타데이터:  <br/>  만든 날짜  <br/>  수정한 날짜  <br/>  만든 사람  <br/>  마지막 수정한 날짜  <br/>  마이그레이션되는 Box 계정 소유의 공유 콘텐츠(사용자 또는 그룹과 명시적으로 공유하는 경우)\*  <br/><br/> \**Box 보고서를 사용하여 외부 계정을 식별합니다. 최종 사용자에게 마이그레이션 후 콘텐츠를 다시 공유하도록 지시합니다.* <br/> | 소유권 기록, 이전 버전 및 메모  <br/>  파일 및 폴더 설명  <br/>  사용자 수준 파일 권한  <br/>  그룹 수준 파일 권한  <br/>  Box 태그와 고급 메타데이터  <br/>  파일 잠금 특성  <br/>  콘텐츠에 포함된 URL 변환  <br/>  휴지통 항목  <br/>  액세스할 수 없거나 손상된 문서  <br/>  차단되거나 비활성 상태인 사용자  <br/>  Box 노트(변환 없이 마이그레이션 시 작동하지 않음)  <br/>  Box 앱, 책갈피, 즐겨찾기 및 워크플로  <br/>  마이그레이션된 Box 계정이 소유하지 않은 콘텐츠(공유 폴더)  <br/>  외부 사용자의 사용 권한 및 기본 메타데이터\*  <br/>  현재 [SharePoint Online 제한 사항을 초과하는 파일 또는 폴더](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Teams용 Dropbox(표준 및 고급)**  <br/> |단일 또는 멀티패스  <br/> | 문서  <br/>  파일 및 폴더 구조  <br/>  사용자 수준 폴더 권한  <br/>  그룹 수준 폴더 권한  <br/>  15GB 미만 파일  <br/>  기본 문서 및 폴더 메타데이터:  <br/>  만든 날짜  <br/>  수정한 날짜  <br/>  만든 사람  <br/>  마지막 수정 날짜  <br/> 공유 팀 폴더 및 콘텐츠 <br/> 마이그레이션되는 Dropbox 계정 소유의 공유 콘텐츠(사용자 또는 그룹과 명시적으로 공유하는 경우)\*  <br/> <br/> \**Dropbox 보고서를 사용하여 외부 계정을 식별합니다. 최종 사용자에게 마이그레이션 후 콘텐츠를 다시 공유하도록 지시합니다.* <br/> | 소유권 기록, 이전 버전 및 메모 <br/>  파일 및 폴더 설명 <br/>  사용자 수준 파일 권한  <br/>  그룹 수준 파일 권한    <br/> 고급 메타 데이터  <br/>  파일 잠금 특성  <br/>  콘텐츠에 포함된 URL 변환  <br/>  휴지통 항목  <br/>  액세스할 수 없거나 손상된 문서  <br/>  연결 해제된 Dropbox 폴더 <br/>  삭제되거나 연결이 끊어진 사용자 <br/>  Dropbox Paper, Showcases 및 Spaces  <br/> Dropbox 앱 및 즐겨찾기(핀/별) <br/> 마이그레이션된 Dropbox 계정이 소유하지 않은 콘텐츠  <br/>  외부 사용자의 사용 권한 및 기본 메타데이터\*  <br/>  현재 [SharePoint Online 제한 사항을 초과하는 파일 또는 폴더](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/> \**Dropbox 보고서를 사용하여 외부 계정을 식별합니다. 최종 사용자에게 마이그레이션 후 콘텐츠를 다시 공유하도록 지시합니다.* <br/> |
   
FastTrack Specialists는 마이그레이션 도중 다음을 수행합니다.  
- 선택한 마이그레이션 시나리오에 대한 프로세스 및 접근 방식을 다루는 마이그레이션 연습 워크숍을 실시합니다.   
- 시나리오에 따라 적절하게 평가 및 마이그레이션 도구의 필수 구성 요소를 제공합니다.  
- 평가 및 마이그레이션 목적으로 원본 및 대상 환경에 마이그레이션 팀이 액세스하기 위한 필수 구성 요소를 제공합니다.   
- 평가 대상/원본 환경에 대한 평가를 수행하기 위한 평가 도구를 제공하거나 네이티브 원본 플랫폼 기능을 사용하여 평가 보고서를 만드는 방법에 대한 지침을 제공합니다.    
- 평가 및 마이그레이션 도구의 배포와 실행을 지원합니다(해당되는 경우).   
- 콘텐츠 마이그레이션을 준비할 때 마이그레이션 인프라를 구성합니다(해당되는 경우).    
- 제한된 테스트 마이그레이션을 수행하여 마이그레이션 인프라 및 필수 구성 요소를 확인합니다.    
- 기본 형태의 대상 비즈니스용 OneDrive 사이트를 마이그레이션의 일부로 프로비전합니다.    
- 빠른 마이그레이션 전에 파일럿 마이그레이션을 1회 수행합니다.
- 선택한 시나리오의 마이그레이션 일정에 대한 지침을 제공합니다.   
- 고객이 제공하고 FastTrack 리소스가 유효성을 검사한 마이그레이션 일정에 따라 콘텐츠의 빠른 마이그레이션 과정을 진행합니다.   
- 각 마이그레이션 기간 후에 마이그레이션 결과를 제공합니다.   
- 빠른 마이그레이션 문제 분류에 참여하고 가능한 수정 옵션에 대한 지침을 제공합니다. 
- 빠른 각 마이그레이션 기간에 대한 최종 마이그레이션 보고서를 제공합니다.   
- 마이그레이션이 완료되고 최대 5일 내에 진행되는 사용자 승인 테스트 동안 마이그레이션 후 지원을 제공합니다.
   
마이그레이션 도중 다음을 수행합니다.
- Provide project resources recommended for assessment and migration activities. These include:
  - 프로젝트 관리
  - UAT.
  - 원본 및 대상 콘텐츠 플랫폼을 담당하는 관리자
- 평가 및 마이그레이션 작업을 위한 인프라 필수 구성 요소를 제공합니다(필요한 경우).   
- 마이그레이션 작업을 수행할 수 있도록 FastTrack 전문가에게 원본 및 대상 환경에 대한 액세스 및 사용 권한을 제공합니다(필요한 경우).  
    > [!NOTE]
    > Migrations only use accounts that adhere to security requirements defined during onboarding. If you don't use such accounts, you may experience migration delays. 
- FastTrack에서 제공하는 평가 도구를 설치하고 평가 데이터 수집 작업을 완료합니다(해당되는 경우).
- FastTrack에서 제공하는 마이그레이션 소프트웨어를 온-프레미스에서 설치합니다(해당되는 경우).  
- FastTrack에서 제공하는 수정 보고서에 대략적으로 설명된 수정 작업을 완료합니다(해당되는 경우).   
- FastTrack 템플릿 및 지침을 사용하여 마이그레이션 일정을 제공합니다. 
- 정의된 방법에 대한 일정과 각 마이그레이션 이벤트에 대해 마이그레이션하는 데 필요한 특정 사용자 데이터 목록을 제공합니다.
- Drop user data from the schedule until 24 hours in advance of the migration batch. This should correspond to the final migration batch.
- 마이그레이션 품질 보증 및 사용자 승인 테스트를 수행합니다.   
- 마이그레이션 후 마이그레이션 수정을 수행합니다(해당하는 경우).  
- 변경 관리 및 최종 사용자 의사 소통을 계획하고 구현합니다(해당되는 경우).  
- 평가 및 마이그레이션 활동을 성공적으로 완료하는 데 필요한 원본 시스템 및 장치에 대한 변경 사항을 관리하고 구성합니다.
    
> [!NOTE]
> Microsoft는 파일 마이그레이션의 속도를 보장하지 않습니다. 


