<div align="center">
  <img src="./assets/profile-hero.svg" alt="Secure Systems Builder" width="100%" />
</div>

<p align="center">
  <a href="mailto:tlstpstpdl11@gmail.com">
    <img src="https://img.shields.io/badge/Email-tlstpstpdl11%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/ssuukko">
    <img src="https://img.shields.io/badge/GitHub-ssuukko-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <img src="https://img.shields.io/badge/Focus-Security%20%26%20Infrastructure-0F766E?style=flat-square" alt="Focus" />
</p>

<p align="center">
  자동화된 도구에만 의존하지 않고, 입력값이 어디서 들어와 어떻게 처리되고 어디에 출력되는지 끝까지 추적합니다.<br/>
  보안 취약점 조치, WAS 인프라 이전, 온사이트 배포, 실시간 AI 웹 구현까지 운영 환경의 문제를 직접 해결합니다.
</p>

<div align="center">
  <img src="./assets/section-line.svg" width="100%" alt="" />
</div>

<div align="center">
  <img width="92%" alt="3D Github Contribution" src="./profile-3d-contrib/profile-gitblock.svg" />
</div>

<br/>

## Impact

| 보안 | 인프라 | 현장 대응 | 모던 웹 |
|:---:|:---:|:---:|:---:|
| **1,600여 건** | **WAS06 → WAS08** | **KOTSA 김천 온사이트** | **AI + Realtime** |
| Sparrow 웹 취약점 전량 분석 및 조치 | 운영 서버 복제, 마이그레이션, 신규 도메인 라우팅 | 직접 반영, 점검, 안정화 | Next.js, MediaPipe, Socket.IO |

## Profile

> “동작하는 코드”보다 **운영 환경에서 설명 가능한 코드**를 더 중요하게 생각합니다.

- **Security Hardening:** XSS 취약점을 단순 치환으로 덮지 않고, 요청 파라미터가 JSP 화면에 렌더링되는 경로를 추적합니다.
- **Enterprise Backend:** 복잡한 업무 조건에서는 SQL과 데이터 흐름이 명시적으로 보여야 한다고 봅니다.
- **Infrastructure Ownership:** 코드 작성에서 멈추지 않고 서버 이전, 도메인 연결, 현장 반영, 안정화까지 확인합니다.
- **Full-cycle Builder:** Java/Spring 백엔드부터 JSP/JSTL, Next.js, 실시간 통신, AI 연동까지 서비스 흐름 전체를 다룹니다.

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/Java-111827?style=for-the-badge&logo=openjdk&logoColor=F97316" alt="Java" />
  <img src="https://img.shields.io/badge/Spring-111827?style=for-the-badge&logo=spring&logoColor=6DB33F" alt="Spring" />
  <img src="https://img.shields.io/badge/Tomcat-111827?style=for-the-badge&logo=apachetomcat&logoColor=F8DC75" alt="Tomcat" />
  <img src="https://img.shields.io/badge/MyBatis-111827?style=for-the-badge&logo=databricks&logoColor=FF3621" alt="MyBatis" />
  <img src="https://img.shields.io/badge/Map%20%2B%20VO%20%2B%20MyBatis-2563EB?style=for-the-badge&logo=java&logoColor=white" alt="Map + VO + MyBatis" />
</p>

<p>
  <img src="https://img.shields.io/badge/Next.js-111827?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/JSP-111827?style=for-the-badge&logo=java&logoColor=F97316" alt="JSP" />
  <img src="https://img.shields.io/badge/JSTL-111827?style=for-the-badge&logo=apache&logoColor=D22128" alt="JSTL" />
  <img src="https://img.shields.io/badge/MediaPipe-111827?style=for-the-badge&logo=google&logoColor=4285F4" alt="MediaPipe" />
  <img src="https://img.shields.io/badge/Socket.IO-111827?style=for-the-badge&logo=socketdotio&logoColor=white" alt="Socket.IO" />
</p>

<p>
  <img src="https://img.shields.io/badge/Linux-111827?style=for-the-badge&logo=linux&logoColor=FCC624" alt="Linux" />
  <img src="https://img.shields.io/badge/Sparrow-7F1D1D?style=for-the-badge&logo=securityscorecard&logoColor=white" alt="Sparrow" />
  <img src="https://img.shields.io/badge/Static%20Analysis-7F1D1D?style=for-the-badge&logo=sonarqube&logoColor=white" alt="Static Analysis" />
  <img src="https://img.shields.io/badge/WAS%20Migration-374151?style=for-the-badge&logo=apachetomcat&logoColor=F8DC75" alt="WAS Migration" />
</p>

## Selected Work

### 01. 모빌리티 규제 샌드박스 시스템 보안 고도화

**문제:** Sparrow 정적 분석 툴에서 대량의 웹 취약점이 검출되어 운영 시스템의 보안 기준 충족이 필요했습니다.  
**해결:** 취약점을 화면, 요청 파라미터, 출력 위치, 렌더링 방식 기준으로 분류하고 XSS 발생 가능 경로를 추적했습니다.  
**성과:** **1,600여 건**의 웹 취약점을 전량 분석 및 조치했습니다. 외부 보안 라이브러리나 Filter를 단순 도입하지 않고, **JSTL Core**와 순수 코드 수정으로 방어 로직을 구현했습니다.

### 02. 서버 인프라 및 배포 관리

**문제:** 기존 WAS06 운영 환경을 WAS08로 이전해야 했고, 서비스 영향 없이 동일한 실행 환경을 재현해야 했습니다.  
**해결:** WAS 설정, 배포 구성, 서버 환경 차이를 확인하며 **WAS06 → WAS08** 복제 및 마이그레이션을 수행했습니다.  
**성과:** 신규 도메인 라우팅을 연결하고, **한국교통안전공단(KOTSA, 김천) 온사이트**에서 직접 반영 및 안정화를 진행했습니다.

### 03. AI 실시간 면접 시뮬레이션 시스템

**문제:** 브라우저에서 면접자의 얼굴 반응을 실시간으로 분석하고, 사용자와 시스템 간 양방향 상호작용을 제공해야 했습니다.  
**해결:** **Next.js**, **MediaPipe**, **Socket.IO**를 활용해 클라이언트 기반 안면 분석과 실시간 이벤트 통신을 연결했습니다.  
**성과:** 모던 프론트엔드, AI 분석, 실시간 통신을 하나의 면접 시뮬레이션 경험으로 통합했습니다.

### 04. 알림장 프로젝트

**문제:** 종이 알림장은 분실과 전달 지연이 발생하고, 단체 채팅방은 중요한 공지가 쉽게 묻히는 문제가 있었습니다.  
**해결:** 단순 채팅이 아니라 공지 전달, 대상자 확인, 커뮤니케이션 흐름을 분리한 소통 구조를 설계했습니다.  
**성과:** 학부모와 교사 사이에서 정보 전달의 **정확성**과 추적 가능성을 높이는 플랫폼을 구축했습니다.

## Architecture Preference

```text
Map      요청 파라미터를 유연하게 수용하고 흐름을 추적합니다.
VO       핵심 도메인 데이터를 명확한 객체로 표현합니다.
MyBatis  SQL과 결과 매핑을 명시적으로 관리해 운영 중 원인 분석을 쉽게 만듭니다.
```

복잡한 엔터프라이즈 업무에서는 단순 추상화보다 데이터 흐름의 설명 가능성이 중요하다고 봅니다.  
그래서 **Map + VO + MyBatis** 기반 구조를 선호하며, 장애가 났을 때 어떤 입력이 어떤 SQL과 화면 출력으로 이어졌는지 설명할 수 있는 코드를 지향합니다.

<details>
<summary><strong>Troubleshooting Notes</strong></summary>

- 정적 분석 결과를 단순 문자열 치환으로 제거하지 않고, 실제 렌더링 맥락을 기준으로 위험도를 판단했습니다.
- 공통 Filter 도입 시 기존 화면에 발생할 수 있는 사이드 이펙트를 고려해 JSP/JSTL 레벨의 수정 전략을 선택했습니다.
- WAS 설정, 실행 경로, 배포 파일, 도메인 라우팅, 반영 후 확인 절차를 함께 점검했습니다.
- 개발 환경과 운영 환경의 차이를 전제로 두고, 현장에서 즉시 확인 가능한 안정화 기준을 잡았습니다.

</details>

## Projects & Stats

<div align="center">
  <a href="https://github.com/ssuukko/allimjang">
    <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=ssuukko&repo=allimjang&hide_border=true&theme=default&title_color=111827&text_color=374151&icon_color=2563EB" alt="allimjang" />
  </a>
  <a href="https://github.com/ssuukko/vocaca">
    <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=ssuukko&repo=vocaca&hide_border=true&theme=default&title_color=111827&text_color=374151&icon_color=2563EB" alt="vocaca" />
  </a>
</div>

<br/>

<div align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=ssuukko&show_icons=true&hide_border=true&rank_icon=github&theme=default&title_color=111827&text_color=374151&icon_color=2563EB&include_all_commits=true&count_private=true" alt="GitHub Stats" />
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ssuukko&layout=compact&hide_border=true&theme=default&title_color=111827&text_color=374151&langs_count=8" alt="Top Languages" />
</div>
