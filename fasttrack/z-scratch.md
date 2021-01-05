## <a name="security-and-compliance"></a>보안 및 규정 준수

<table>
<thead>
<tr class="header">
<th><strong>서비스</strong></th>
<th><strong>FastTrack 지침 세부 정보</strong></th>
<th><strong>원본 환경 요구 조건</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
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
<tr class="even">
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
<li> 앱 <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-gove">커넥터를 사용하여</a> 주요 앱을 연결합니다.</li>
<li> 조건부 액세스 및 Cloud App Security 포털에서 조건부 액세스 앱 컨트롤을 설정하여 실시간 세션 컨트롤을 적용합니다.</li>
<li> Cloud App Security 및 클라우드 검색 대시보드 배포</li>
<li> 조직의 우선 순위에 따라 앱 위험 점수를 사용자 지정합니다.</li>
<li> 앱 태그 및 범주 만들기</li>
<li> 앱에 대한 인가 및 비확인.</li>
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
<li> 개념 증명으로 Cloud App Security 배포</li>
</ul></td>
</tr>



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
<li>  다음에 대한 배포 지침, 구성 지원 및 교육 제공 </li>
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
<li> 사용자, 컴퓨터, 측면 이동 경로 또는 엔터티 조사 </li>
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


<table>
<thead>
<TABLE  CELLPADDING="2" CELLSPACING="2" WIDTH="100%">
<tr class="header">
<TD width 15%><strong>서비스</strong></TD>
<TD width 50%><strong>FastTrack 지침 세부 정보</strong></TD>
<TD width 25%><strong>원본 환경 기대치</strong></TD>
<TR>
</thead>
<tbody>


</tr>
</tbody>
</table>