<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=260&color=0:020617,40:0F172A,70:1D4ED8,100:0EA5E9&text=SSUUKKO&fontColor=FFFFFF&fontAlign=50&fontAlignY=40&fontSize=80&desc=Full-Stack%20Developer%20%7C%20Product-Minded%20Engineer&descAlign=50&descAlignY=60&descSize=16&animation=fadeIn" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&pause=900&color=38BDF8&center=true&vCenter=true&width=750&lines=아이디어를+실제로+동작하는+제품으로+만듭니다.;화면+%2F+로직+%2F+데이터+%2F+배포를+혼자+끝냅니다.;완성까지+가는+개발자입니다." alt="Typing SVG" />
</p>

<p align="center">
  <a href="mailto:tlstpstpdl11@naver.com">
    <img src="https://img.shields.io/badge/Email-03C75A?style=for-the-badge&logo=naver&logoColor=white" />
  </a>
  <a href="https://github.com/ssuukko">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

## 🧑‍💻 About Me

> 개발 경력 2년 미만. 그러나 기획부터 배포까지 **혼자 끝낸 경험**이 있습니다.

저는 "시킨 것만 하는 개발자"가 되기 싫었습니다.  
그래서 처음부터 직접 설계하고, 구현하고, 배포하고, 고쳤습니다.  
아직 부족한 점이 많다는 걸 알기 때문에, 매일 조금씩 더 잘하는 방향으로 움직이고 있습니다.

```ts
const ssuukko = {
  identity   : 'Full-Stack Developer (Junior → Growing Fast)',
  languages  : ['TypeScript', 'Java'],
  approach   : 'Build → Ship → Learn → Rebuild Better',
  values     : ['완성', '명확함', '사용자 관점', '꾸준함'],
  currently  : '실제 유저가 쓰는 제품 만들기',
}
```

---

## 🔨 What I Actually Build

| 레이어 | 내가 하는 것 |
|:---:|:---|
| **Product** | 문제 정의, 사용자 흐름 설계, 범위 조정 |
| **Interface** | React 기반 UI, 상태 관리, 사용자 인터랙션 |
| **Logic** | 유효성 검증, 데이터 흐름, 예외 처리 |
| **Backend** | REST API · WebSocket · DB 설계 · 인증 처리 |
| **Delivery** | Docker · 클라우드 배포 · 환경 분리 · 반복 개선 |

---

## ⚙️ Tech Stack

**Frontend**

<p>
  <img src="https://img.shields.io/badge/TypeScript-0F172A?style=for-the-badge&logo=typescript&logoColor=3178C6" />
  <img src="https://img.shields.io/badge/JavaScript-0F172A?style=for-the-badge&logo=javascript&logoColor=F7DF1E" />
  <img src="https://img.shields.io/badge/React-0F172A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Next.js-0F172A?style=for-the-badge&logo=nextdotjs&logoColor=FFFFFF" />
  <img src="https://img.shields.io/badge/Vite-0F172A?style=for-the-badge&logo=vite&logoColor=646CFF" />
  <img src="https://img.shields.io/badge/Tailwind-0F172A?style=for-the-badge&logo=tailwindcss&logoColor=06B6D4" />
</p>

**Backend**

<p>
  <img src="https://img.shields.io/badge/Java-0F172A?style=for-the-badge&logo=openjdk&logoColor=ED8B00" />
  <img src="https://img.shields.io/badge/Spring Boot-0F172A?style=for-the-badge&logo=springboot&logoColor=6DB33F" />
  <img src="https://img.shields.io/badge/Node.js-0F172A?style=for-the-badge&logo=nodedotjs&logoColor=5FA04E" />
  <img src="https://img.shields.io/badge/WebSocket-0F172A?style=for-the-badge&logo=socket.io&logoColor=FFFFFF" />
</p>

**Data & Infra**

<p>
  <img src="https://img.shields.io/badge/Supabase-0F172A?style=for-the-badge&logo=supabase&logoColor=3FCF8E" />
  <img src="https://img.shields.io/badge/PostgreSQL-0F172A?style=for-the-badge&logo=postgresql&logoColor=4169E1" />
  <img src="https://img.shields.io/badge/MySQL-0F172A?style=for-the-badge&logo=mysql&logoColor=4479A1" />
  <img src="https://img.shields.io/badge/Docker-0F172A?style=for-the-badge&logo=docker&logoColor=2496ED" />
  <img src="https://img.shields.io/badge/Git-0F172A?style=for-the-badge&logo=git&logoColor=F05032" />
  <img src="https://img.shields.io/badge/Linux-0F172A?style=for-the-badge&logo=linux&logoColor=FCC624" />
</p>

---

## 🚀 Projects

### 📋 [allimjang](https://github.com/ssuukko/allimjang) — 디지털 알림장 플랫폼

> 종이 알림장과 단체 채팅방의 불편함을 해소하는 교사-학부모 소통 플랫폼

**문제:** 기존 종이 알림장은 분실·지연이 잦고, 단체 채팅방은 공지 누락과 열람 확인이 불가능  
**해결:** 공지사항 CRUD + 수신자별 읽음 추적 + WebSocket 실시간 채팅 + 역할 기반 접근 제어

| | |
|:---|:---|
| **Stack** | Java 17 · Spring Boot 3 · Spring Security · WebSocket(STOMP) · Thymeleaf · MyBatis · PostgreSQL |
| **Infra** | Docker · Render 배포 · Neon Cloud DB |
| **특징** | 공지 대상 선택 배포 / 읽음 상태 실시간 추적 / 1:1 DM 채팅 / 세션 기반 인증 |

<a href="https://github.com/ssuukko/allimjang">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=ssuukko&repo=allimjang&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=38BDF8&text_color=E5E7EB&icon_color=22C55E" />
</a>

---

### 🔤 [vocaca](https://github.com/ssuukko/vocaca) — 어휘 학습 웹앱

> 단어를 직접 등록하고 반복 학습할 수 있는 개인 어휘 관리 앱

**문제:** 외부 앱은 내 학습 맥락에 맞지 않고, 직접 만든 단어장이 없었음  
**해결:** 단어 등록·관리·학습 플로우를 직접 설계하고 Supabase Auth로 개인화

| | |
|:---|:---|
| **Stack** | React · TypeScript · Vite · Supabase · Tailwind CSS |
| **Infra** | Vercel 배포 |
| **링크** | [vocaca.vercel.app](https://vocaca.vercel.app) |

<a href="https://github.com/ssuukko/vocaca">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=ssuukko&repo=vocaca&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=38BDF8&text_color=E5E7EB&icon_color=22C55E" />
</a>

---

## 📈 GitHub Stats

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=ssuukko&show_icons=true&hide_border=true&rank_icon=github&theme=tokyonight&bg_color=0D1117&title_color=38BDF8&icon_color=22C55E&text_color=E5E7EB&include_all_commits=true&count_private=true" />
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ssuukko&layout=compact&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=38BDF8&text_color=E5E7EB&langs_count=6" />
</p>

## 🗺️ 3D Contribution

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./profile-3d-contrib/profile-night-green-animate.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./profile-3d-contrib/profile-green-animate.svg" />
  <img width="100%" src="./profile-3d-contrib/profile-night-green-animate.svg" alt="3D Contribution Graph" />
</picture>

---

## 🌱 Now & Next

```
지금 하고 있는 것
├── allimjang 기능 확장 및 코드 개선
├── vocaca 실사용 피드백 반영
└── 사이드 프로젝트 → 배포 → 유저 확보 사이클 반복

다음 목표
├── 코드 리뷰를 주고받을 수 있는 팀 환경 경험
├── 서비스 규모가 커질 때의 아키텍처 판단 경험
└── "이 사람이 만든 거 써봤는데 좋던데" 소리 듣기
```

---

## 🧭 개발 원칙

```
완성하지 않으면 없는 것이다.        →  시작한 것은 배포까지 간다
기술은 수단이지 목적이 아니다.      →  문제부터 정의한다
복잡함은 이해 부족에서 온다.        →  구조를 단순하게 만든다
나쁜 코드는 느린 것이 아니라        →  읽기 어려운 것이다
```

---

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=130&section=footer&color=0:0EA5E9,50:1D4ED8,100:020617&reversal=false" />
