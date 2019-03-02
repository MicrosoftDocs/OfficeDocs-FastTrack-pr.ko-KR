---
title: 원본 환경 요구 조건
description: EMS에 대 한 fasttrack 센터 혜택을 사용 하기 위한 원본 환경 요구 사항
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 03/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 6b3a5ed24ac254c3a989a584df0cbd89533ff1af
ms.sourcegitcommit: 5abb49be2bfa99110f17245839c3468318b8a3db
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/01/2019
ms.locfileid: "30359986"
---
# <a name="source-environment-expectations"></a>원본 환경 요구 조건

[EMS (Enterprise Mobility + Security)에 대 한 fasttrack 센터 혜택](EMS-fasttrack-benefit-for-EMS.md) 을 사용 하 여 microsoft Azure Active Directory Premium 및 microsoft Intune을 사용할 수 있도록 하면 다음 섹션에서 설명 하는 요구 사항을 충족 해야 합니다.

조직의 EMS (Enterprise Mobility + Security) 또는 단일 콘솔의 다양 한 id 관리를 사용 하는 개별 서비스와 통합 하려는 조직에 온-프레미스 Active Directory가 이미 있을 수 있습니다. EMS (Enterprise Mobility + Security)에 대 한 fasttrack 센터 혜택에는 Azure Active directory를 기존 온-프레미스 Active directory 환경과 통합 하는 데 도움이 됩니다.

다음 표에는 온-탑재 시 기존 원본 환경의 기대치가 나와 있습니다.

|작업|원본 환경 요구 조건|
|------------|----------------------------------|
|코어 온-탑재|다음 포리스트 구성을 사용 하 여 기능 포리스트 수준이 Windows Server 2008 이상으로 설정 된 Active Directory 포리스트:<br /><br />-단일 Active Directory 포리스트<br />-다중 Active Directory 포리스트 </br></br>**참고**: 모든 다중 포리스트 구성에서 AD FS (Active Directory Federation Services) 배포는 fasttrack 센터 혜택에 대 한 범위를 벗어납니다.|
|Azure AD Premium 온-탑재|azure ad 및 azure ad premium 기능과의 통합을 방지 하는 식별 된 문제의 수정을 포함 하는 azure ad premium에 대 한 온-프레미스 Active Directory 및 해당 환경이 준비 되었습니다.|
|Intune 온-탑재| IT 관리자는 Intune을 사용 하 여 wifi 및 vpn 프로필 배포를 계획할 때 프로덕션 환경에서 이미 작동 하는 기존 인증 기관, WiFi 및 vpn 인프라를 사용 해야 합니다.<br /><br /> **참고**: 서비스 혜택에는 인증 기관, WiFi, VPN 인프라 또는 Apple MDM 푸시 인증서의 설정 또는 구성에 대 한 지원이 포함 되지 않습니다.  |
|Comanagement|Comanagement IT 관리자는 구성 관리자 및 Intune을 사용 하 여 Windows 10 장치를 동시에 관리할 수 없도록 하는 문제에 대 한 수정이 포함 될 수 있는 온-프레미스 환경을 준비 합니다.<br /><br />**참고**: fasttrack 서비스 혜택에는 configuration manager 사이트 서버 및/또는 configuration manager 클라이언트를 Windows 10 장치에서 Comanagement를 지 원하는 데 필요한 최소 요구 사항으로 설정 하거나 업그레이드 하는 데 대 한 지원이 포함 되어 있지 않습니다. |
|windows defender Advanced Threat Protection과 통합 된 Intune (windows defender ATP)|회사 보안 요구 사항에 따라 Windows Defender ATP 구독이 활성화 및 구성 되었습니다.<br /><br />**참고**: fasttrack 서비스 혜택은 windows Defender ATP와 Intune을 통합 하는 데 도움이 되며, windows 10 위험 수준 평가를 기반으로 하는 장치 준수 정책 만들기에 대 한 지원을 제공 합니다. fasttrack 서비스 혜택은 Windows Defender ATP 및 해당 보안 센터 콘솔을 구입, 라이선스, 정품 인증 또는 사용 하는 데 도움이 되지 않습니다. |
|Windows Autopilot|IT 관리자는 하드웨어 공급 업체가 사용자를 대신 하 여 하드웨어 id를 사용자에 게 업로드 하거나 Windows Autopilot 서비스에 업로드 하는 방식으로 해당 장치를 조직에 등록 하는 일을 담당 합니다. |
|Intune을 사용 하 여 iOS 및 Android 용 Outlook을 안전 하 게 배포|<br /><br />-Office 365의 Azure AD에서 사용자 id를 사용할 수 있습니다.<br />-사용자 라이선스를 할당 하 여 exchange Online 또는 하이브리드 exchange를 구성 합니다.<br />|

> [!NOTE]
> **자세한 정보를 원하십니까?** 
>  [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>다음 단계

[EMS 온 보 딩 단계에 대 한 fasttrack 센터 혜택](EMS-onboarding-phases.md)
