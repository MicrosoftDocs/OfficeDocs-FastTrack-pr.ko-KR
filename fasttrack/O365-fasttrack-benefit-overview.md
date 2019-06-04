---
title: FastTrack 센터 혜택 개요
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 06/04/2019
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: Office 365용 FastTrack 센터 혜택를 사용하여 FastTrack Specialists와 원격으로 작업하여 Office 365 환경을 사용하고 조직 내에서 계획을 구현하고 사용하도록 준비합니다. 자격에 대한 자세한 내용은 Office 365용 FastTrack 센터 혜택을 참조하세요.
ms.openlocfilehash: 9c686d7d007fcc6d661ffe81050c96122989a899
ms.sourcegitcommit: 0e76ab0f36619dee923201098936573be14b4560
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/03/2019
ms.locfileid: "34673465"
---
# <a name="fasttrack-center-benefit-overview"></a>FastTrack 센터 혜택 개요

Office 365용 FastTrack 센터 혜택를 사용하여 FastTrack Specialists와 원격으로 작업하여 Office 365 환경을 사용하고 조직 내에서 계획을 구현하고 사용하도록 준비합니다. 자격에 대한 자세한 내용은 [Office 365용 FastTrack 센터 혜택](O365-fasttrack-benefit-for-office-365.md)을 참조하세요.
  
다음 항목에 대해 설명합니다.
- [FastTrack 프로세스](O365-fasttrack-process.md) 
- [원본 환경 요구 조건](O365-source-environment-expectations.md)
- [온보딩 및 마이그레이션 단계](O365-onboarding-and-migration.md)
- [데이터 마이그레이션](O365-data-migration.md)
- [FastTrack 책임](O365-fasttrack-responsibilities.md)
- [사용자의 업무](O365-your-responsibilities.md) 
- [부록 A: IBM Domino에서 Exchange Online으로 마이그레이션](O365-from-ibm-domino-to-exchange-online.md)
- [부록 B: FastTrack 센터의 추가 장점](O365-fasttrack-additional-benefits.md)
- [부록 C - FastTrack Center HIPAA 사업 협력 계약](O365-hipaa-business-associate-agreement.md)
- [부록 D - Office 365 US Government용 FastTrack Center 혜택 개요](US-Gov-appendix-overview.md)
    
온보딩이 완료될 때 Office 365 테넌트가 만들어집니다. 라이선스가 있는 사용자는 다음 ID 옵션 중 하나를 사용하여 Office 365에 액세스할 수 있습니다.
- 고유한 Office 365 계정이 있는 클라우드 ID.
- Azure Active Directory Connect(암호 해시 동기화 또는 통과 인증)를 사용하여 온-프레미스 Active Directory에서 동기화된 Office 365 계정과 동기화된 ID. 다음 상황의 고객을 위한 것입니다.
  - 단일 Active Directory 포리스트 환경.
  - 다중 포리스트 Active Directory 토폴로지를 지원합니다. 지원되는 토폴로지는 [원본 환경 요구 조건](O365-source-environment-expectations.md)을 참조하세요.
- 다음 Office 365 계정을 갖는 페더레이션 ID
  - 다음 고객을 위해 Azure Active Directory Connect 도구를 사용하여 Active Directory에서 동기화됨:
      - 단일 Active Directory 포리스트 구성
      - 단일 Active Directory 계정 포리스트("로그온 포리스트"라고도 함) 및 단일 Active Directory 리소스 포리스트 구성
  - 다음의 온-프레미스 AD FS(Active Directory Federation Services) 인프라를 사용하여 구성됨:
      - 온-프레미스 Active Directory의 Windows Server 2012 R2 이후 AD FS 역할과 페더레이션되었습니다.
      - 필요한 경우, 온-프레미스 AD FS 인프라를 인터넷에 게시하는 데 사용한 Windows Server 2012 R2 이후 WAP(Windows 응용 프로그램 프록시) 역할.
    > [!NOTE]
    > AD FS 및 WAP 배포 및 구성은 온-프레미스 환경에서 [Azure AD Connect 구성 마법사](https://go.microsoft.com/fwlink/?linkid=844794)를 사용하여 수행됩니다. 
  
- 이제 허가된 사용자가 [적합한 서비스 및 계획](M365-eligible-services-and-plans.md)에 액세스할 수 있습니다.
    

 
