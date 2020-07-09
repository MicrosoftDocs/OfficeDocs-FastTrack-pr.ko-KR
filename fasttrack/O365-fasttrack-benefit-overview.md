---
title: FastTrack 센터 혜택 개요
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: With FastTrack Center Benefit for Office 365, you work remotely with FastTrack Specialists to get your Office 365 environment ready for use and plan rollout and usage within your organization. To learn more about eligibility, see FastTrack Center Benefit for Office 365.
ms.openlocfilehash: 3537f6effa5bd2c65f542496ea42ab70075621ce
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011336"
---
# <a name="fasttrack-center-benefit-overview"></a>FastTrack 센터 혜택 개요

With FastTrack Center Benefit for Office 365, you work remotely with FastTrack Specialists to get your Office 365 environment ready for use and plan rollout and usage within your organization. To learn more about eligibility, see [FastTrack Center Benefit for Office 365](O365-fasttrack-benefit-for-office-365.md).
  
다음 항목에 대해 설명합니다.
- [FastTrack 프로세스](O365-fasttrack-process.md) 
- [원본 환경 요구 조건](O365-source-environment-expectations.md)
- [온보딩 및 마이그레이션 단계](O365-onboarding-and-migration.md)
- [데이터 마이그레이션](O365-data-migration.md)
- [FastTrack 책임](O365-fasttrack-responsibilities.md)
- [사용자의 업무](O365-your-responsibilities.md) 
- [부록 A - FastTrack 센터 추가 혜택](O365-fasttrack-additional-benefits.md) 
- [부록 B - FastTrack Center HIPAA 사업 관련 계약](O365-hipaa-business-associate-agreement.md)
- [부록 C - Office 365 미국 정부용 FastTrack 센터 혜택 개요](US-Gov-appendix-overview.md)
    
Your Office 365 tenant is created at the completion of onboarding. Licensed users can access Office 365 by using one of the following identity options:
- 고유한 Office 365 계정이 있는 클라우드 ID.
- Synchronized Identities with Office 365 accounts synchronized from your on-premises Active Directory with Azure Active Directory Connect (Password Hash Sync or Pass-through Authentication). These are for customers with:
  - 단일 Active Directory 포리스트 환경.
  - Supported multi-forests Active Directory topology. For supported topologies, see [Source Environment Expectations](O365-source-environment-expectations.md).
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

