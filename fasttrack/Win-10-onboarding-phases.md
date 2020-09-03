---
title: 온보딩 단계
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: None
ms.collection: FastTrack
description: Windows 10 온보딩은 시작, 평가, 재구성 및 사용의 네 가지 기본 단계로 구성됩니다.
ms.openlocfilehash: 02067415d8fa34d353a96d811c18fde30d18e8ab
ms.sourcegitcommit: de2cc20b4ab297633cb254d42532719022bb8d99
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/02/2020
ms.locfileid: "47338476"
---
# <a name="onboarding-phases"></a>온보딩 단계

> [!CAUTION]
> 해당 콘텐츠는 더 이상 최신이 아니므로 제거될 예정입니다. 최신 콘텐츠는 왼쪽 탐색 목차를 사용합니다.

Windows 10 온보딩은 시작, 평가, 재구성 및 사용의 네 가지 기본 단계로 구성됩니다.

## <a name="initiate"></a>시작

이 단계에서는 온보딩 프로세스를 논의하고, 데이터를 확인하며, 킥오프 모임을 설정합니다. 여기에는 사용자와 함께 Windows 10 목적을 이해하는 작업이 포함됩니다.

## <a name="assess"></a>평가

FastTrack 전문가는 사용자와 함께 원본 환경과 요구 사항을 평가합니다. Microsoft Endpoint Configuration Manager가 Windows 10 배포를 지원하는 데 필요한 수준으로 업그레이드되었는지 확인하세요. 

Windows 10 앱을 평가하는 데 권장되는 옵션을 제공합니다. FastTrack은 Desktop Analytics 사용을 가능하게 하는 지침을 제공하고 Desktop Analytics 배포 계획 작성을 안내합니다.

FastTrack은 Configuration Manager에서 Office 365 준비 대시보드를 활용하거나 Office용 독립형 준비 도구 키트를 사용하여 Microsoft 365 앱 호환성 평가를 안내할 수도 있습니다. 사용 가능한 서비스에 관한 자세한 내용은 [Office 365용 FastTrack Center 혜택](O365-fasttrack-benefit-for-office-365.md)을 참조합니다. 

FastTrack은 또한 Microsoft Intune과 함께 클라우드 연결 구성 관리자를 포함 또는 단독 클라우드 관리 솔루션으로서 Intune을 배포하여 사용자의 최신 관리 전략을 평가합니다.

## <a name="remediate"></a>수정

원본 환경을 기준으로 재구성 작업을 수행하여 온보딩에 필요한 요구 사항을 충족합니다. Microsoft는 환경을 준비하고 성공적인 배포를 위한 최소한의 요구 사항으로 원본 환경을 제공할 수 있도록 이러한 요소가 설정되었는지 확인하는 재구성 검사 목록을 제공합니다. 

## <a name="enable"></a>사용

기존 장치가 필요한 장치 하드웨어 요구 사항을 충족하는 한, FastTrack은 기존 장치를 Windows 10 Enterprise로 업그레이드하기 위한 지침을 제공합니다. 기존 배포 동작을 지원하도록 업그레이드 지침이 제공됩니다. FastTrack은 Windows 10으로의 준비된 업그레이드를 위한 지침을 권장하고 제공합니다. Windows 정리 이미지 설치 및 [Windows Autopilot](EMS-onboarding-phases.md#windows-autopilot) 배포 시나리오에서도 지침을 사용할 수 있습니다. 

Windows 10 배포의 일부로 Configuration Manager를 사용하여 Microsoft 365 앱을 배포하는 방법에 대한 지침을 제공합니다. 관련 서비스에 대한 자세한 내용은 [Microsoft 365 앱](O365-onboarding-and-migration.md#microsoft-365-apps)을 참조하세요.

조직에서 Configuration Manager 환경 또는 Microsoft 365를 사용하여 Windows 10 Enterprise 및 Microsoft 365 앱을 최신 상태로 유지할 수 있는 지침을 제공합니다.

필요한 경우 FastTrack은 고객에게 클라우드 연결 구성 관리자를 Intune에 설치하거나 Intune을 독립 실행형으로 배포하여 최신 관리를 사용할 수 있도록 안내합니다. 관련 서비스에 대한 자세한 내용은 [EMS(Enterprise Mobility + Security)에 대한 FastTrack Center 혜택 프로세스](EMS-fasttrack-process.md)를 참조하세요.

> [!NOTE]
> 배포 및 유지 관리를 위한 기존 계획이나 프로세스가 없는 경우, 적절한 업그레이드 시나리오(권장) 또는 [Windows Autopilot](EMS-onboarding-phases.md#windows-autopilot)을 기준으로 모범 사례 지침을 제공할 수 있습니다.

## <a name="out-of-scope"></a>범위를 벗어남

FastTrack은 다음에 대해서는 지침을 제공하지 않습니다.

- Configuration Manager를 현재 분기로 업그레이드.
- Windows 10 배포용 사용자 지정 이미지 만들기.
- Windows 10 배포용 배포 스크립트 만들기 및 지원
- Windows 10 시스템을 BIOS에서 UEFI(Unified Extensible Firmware Interface)로 변환.
- Windows 10 보안 기능 활성화. 
- PXE(Preboot Execution Environment) 부팅을 위해 WDS(Windows Deployment Services) 구성.
- Windows 10 이미지를 캡처하여 배포하는 데 MDT(Microsoft Deployment Toolkit) 사용.
- USMT(User State Migration Tool) 사용.

  > [!NOTE]
  > 범위를 벗어난 것으로 식별되는 서비스를 지원하려면 [Microsoft 파트너](https://go.microsoft.com/fwlink/?linkid=2080150)에 연락하도록 합니다.

 