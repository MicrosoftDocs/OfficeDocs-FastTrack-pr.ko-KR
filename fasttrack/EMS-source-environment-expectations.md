---
title: 원본 환경 요구 조건
description: EMS용 FastTrack 센터 혜택을 사용하기 위한 원본 환경 요구 사항
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 10/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: c5cb280c3ac2280f0f32fda39258b68ee144e508
ms.sourcegitcommit: 06eb1378c0f3601ca6909765ecacbff23db7e71f
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/01/2019
ms.locfileid: "37342369"
---
# <a name="source-environment-expectations"></a>원본 환경 요구 조건

[EMS(Enterprise Mobility + Security)용 FastTrack 센터 혜택](EMS-fasttrack-benefit-for-EMS.md)을 사용하여 Microsoft Azure Active Directory Premium, Microsoft Intune 및 Azure Information Protection 사용을 준비하는 경우 사용 중인 환경이 다음 섹션에 설명된 요구 조건을 충족해야 합니다.

단일 콘솔에서 풍부한 IT 관리를 사용하는 개별 서비스 또는 EMS(Enterprise Mobility + Security)와 통합하려는 온-프레미스 Active Directory가 조직에 이미 있을 수 있습니다. EMS(Enterprise Mobility + Security)용 FastTrack 센터 혜택에는 기존 온-프레미스 Active Directory 환경에 대한 Azure Active Directory 통합 지원이 포함됩니다.

다음 표에는 온보딩을 위해 기존 원본 환경에서 요구되는 조건이 나와 있습니다.

|활동|원본 환경 요구 조건|
|------------|----------------------------------|
|핵심 온보딩|다음 포리스트 구성을 사용하며 포리스트 기능 수준이 Windows Server 2008 이상으로 설정된 Active Directory 포리스트:<br /><br />- 단일 Active Directory 포리스트<br />- 여러 Active Directory 포리스트 </br></br>**참고**: 모든 다중 포리스트 구성에서 ADFS(Active Directory Federation Services) 배포는 FastTrack 센터 혜택을 받지 않습니다.|
|Azure AD Premium 온보딩|온-프레미스 Active Directory와 해당 환경은 Azure AD Premium용으로 준비되었으며, Azure AD 및 Azure AD Premium 기능과의 통합을 차단하는 식별된 문제를 수정했습니다.|
|Intune 온보딩| IT 관리자는 Intune에서 WiFi 및 VPN 프로필 배포를 계획할 때 기존 인증 기관, WiFi 및 VPN 인프라를 프로덕션 환경에서 이미 사용하고 있어야 합니다.<br /><br /> **참고**: 인증 기관, WiFi, VPN 인프라 또는 Apple MDM 푸시 알림 설정 또는 구성 지원은 서비스 혜택에 포함되지 않습니다.  |
|공동 관리|공동 관리에서 IT 관리자는 온-프레미스 환경 준비를 담당합니다. 여기에는 Configuration Manager와 Intune을 사용하여 Windows 10 장치를 동시에 관리하지 못하도록 하는 문제의 해결이 포함될 수 있습니다.<br /><br />**참고**: Windows 10 장치를 통한 공동 관리를 지원하는 데 필요한 최소 요구 사항에 맞게 Configuration Manager 사이트 서버 및/또는 Configuration Manager 클라이언트를 설정하거나 업그레이드하기 위한 지원은 FastTrack 서비스 혜택에 포함되지 않습니다. |
|Intune과 Windows Defender ATP(Windows Defender Advanced Threat Protection) 통합|Windows Defender ATP 구독이 회사 보안 요구 사항에 따라 활성화되고 구성되었습니다.<br /><br />**참고**: FastTrack 서비스 혜택은 Intune과 Windows Defender ATP의 통합과 Windows 10 위험 수준 평가에 따른 장치 준수 정책 생성을 지원합니다. FastTrack 서비스 혜택은 Windows Defender ATP 및 해당 보안 센터 콘솔의 구입, 라이선싱, 정품 인증 또는 사용을 지원하지 않습니다. |
|Windows Autopilot|IT 관리자는 하드웨어 공급 업체가 사용자를 대신하여 하드웨어 ID를 업로드하거나 Windows Autopilot 서비스로 업로드하는 방법으로 조직에 장치를 등록합니다. |
|Intune을 사용하여 iOS 및 Android용 Outlook을 안전하게 배포|<br /><br />- Office 365용 Azure AD에서 사용자 ID 사용<br />- 사용자 라이선스를 할당하여 Exchange Online 또는 하이브리드 Exchange 구성<br />|
|Azure Information Protection(P2 또는 EMS E5)|<br /><br />고객 요구 조건: <br /> - Azure AD 사용<br />- Windows 또는 iOS(다른 OS 제외) 사용<br /> - Office를 기본 클라이언트로 사용하지 않는 Office 2010 SP2 이후 Office 클라이언트 사용 <br /> - 주 파일 공유 위치 사용  <br /> - AD RMS(Active Directory Rights Management Services)에서 업그레이드 <br /> - 승인된 분류법 보유 <br /> - 보호되는 키 관리에 대한 규정 제한 이해 <br />|
|Azure Information Protection 스캐너|<br /><br /> 고객 요구 조건: <br /> - Windows Server 2012 R2 또는 Windows Server 2016 사용<br /> - 인터넷 연결 <br /> - 로컬 또는 원격 인스턴스에서 Microsoft SQL Server 2012 이상 실행  <br /> - 온-프레미스 Active Directory에 대해 생성되고 Azure AD와 동기화된 서비스 계정  <br /> - AzInfoProtection.exe 다운로드 <br /> - 자동 분류/보호에 대한 레이블 구성<br />|

> [!NOTE]
> **추가 정보가 필요하십니까?**
> [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>다음 단계

[EMS용 FastTrack 센터 혜택 온보딩 단계](EMS-onboarding-phases.md)
