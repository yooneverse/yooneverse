<div align="center">

<br />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,45:2563EB,100:14B8A6&height=260&section=header&text=%EA%B9%80%EC%A7%80%EC%9C%A4&fontSize=68&fontColor=ffffff&fontAlignY=40&desc=Portfolio&descAlignY=60&animation=fadeIn" width="100%" />

### 서비스의 흐름을 이해하고 문제를 실행 가능한 구조로 정리합니다.

<br />

<img src="https://img.shields.io/badge/PM-2563EB?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Planning-0B055A2?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Frontend-0F766E?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/AX-0891B2?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Documentation-14B8A6?style=for-the-badge&logoColor=white" />

<br />
<br />
</div>

<br />

## 소개


> **사용자와 기술 사이의 흐름을 이해하고,  
> 문제가 발생했을 때 원인과 다음 행동을 정리합니다.**

서비스 기획과 개발 프로젝트를 수행하며  
사용자의 요청이 화면, 서버, 데이터로 이어지는 흐름을 경험했습니다.

팀장과 PM으로 일정·역할·산출물을 관리하고,  
화면 명세와 API 명세를 정리해 협업 기준을 만들었습니다.

카카오 지도 운영 업무에서는 월 250건 이상의 장소 데이터를 검토하며  
반복 오류를 11개 유형으로 분류하고 처리 기준을 정리했습니다.

최근에는 Docker 기반 프로젝트를 통해  
서비스 실행 환경, 로그 확인, Health Check, 장애 알림을 구성해 흐름을 설계했습니다.

이 과정에서 AX의 기반이 되는 흐름 속 요소에 대한 이해를 높였습니다.

<br />

---
## 핵심 역량

<table>
  <tr>
    <td align="center" width="25%">
      <strong>01</strong><br />
      <strong>문제 구조화</strong><br />
      <sub>의견과 데이터를<br />실행 과제로 정리</sub>
    </td>
    <td align="center" width="25%">
      <strong>02</strong><br />
      <strong>프로젝트 운영</strong><br />
      <sub>일정·역할·산출물<br />진행 흐름 관리</sub>
    </td>
    <td align="center" width="25%">
      <strong>03</strong><br />
      <strong>서비스 구현</strong><br />
      <sub>웹·모바일 UI와<br />API 연결</sub>
    </td>
    <td align="center" width="25%">
      <strong>04</strong><br />
      <strong>운영 관점</strong><br />
      <sub>로그와 상태 정보를 통한<br />문제 구간 확인</sub>
    </td>
  </tr>
</table>

<br />

```mermaid
flowchart LR
    A["사용자 요구"] --> B["서비스 기획"]
    B --> C["웹·모바일 구현"]
    C --> D["API·데이터 연결"]
    D --> E["실행 환경"]
    E --> F["상태 점검과 운영"]

    classDef default fill:#F8FAFC,stroke:#94A3B8,color:#0F172A,stroke-width:1px;
    classDef point fill:#EFF6FF,stroke:#2563EB,color:#0F172A,stroke-width:1.5px;

    class A,B,C,D,E default;
    class F point;
```

---

## 주요 프로젝트

<table>
  <tr>
    <td width="34%" valign="top">

### [`ops-monitor`](https://github.com/yooneverse/ops-monitor)

**서비스 운영·장애 대응 흐름 설계 AX 인프라 프로젝트**

`Docker` `Nginx` `FastAPI` `PostgreSQL`

- 실행 환경 구성
- Health Check
- 로그 분석
- 장애 알림
- 운영 문서화

  </td>
    <td width="33%" valign="top">

### [`project-eumgil`](https://github.com/yooneverse/project-eumgil)

**보행 약자를 위한 배리어프리 길찾기 서비스**

`Kotlin` `Android` `Accessibility`

- 팀장 및 PM
- 모바일 UI/UX 설계
- 접근성 화면
- API 연동
- 최종 발표

  </td>
    <td width="33%" valign="top">

### [`project-aekkim`](https://github.com/yooneverse/project-aekkim)

**구독 현황 분석과 해지 관리를 지원하는 서비스**

`React` `TypeScript` `AI`

- 웹 UI
- API 연동
- AI 기능 연결
- 서비스 기획
- 발표

  </td>
  </tr>
</table>

<br />

| 프로젝트                                                               | 설명                           | 주요 역할                         |
| ------------------------------------------------------------------ | ---------------------------- | ----------------------------- |
| [`project-arnnect`](https://github.com/yooneverse/project-arnnect) | 신진 예술인의 작품과 전시 경험을 연결한 웹 서비스 | UX 흐름 · 웹 UI · 비주얼 구성 · 발표    |
| [`project_ILU`](https://github.com/yooneverse/project_ILU)         | 사용자 성향과 기업 데이터를 연결한 추천 서비스   | 데이터 분석 · 추천 흐름 · 서비스 기획       |
| [`maeulbot`](https://github.com/yooneverse/maeulbot)               | 일정과 공지 전달을 위한 알림 자동화 프로젝트    | GitHub Actions · 업무 자동화 · 문서화 |

---

## 대표 프로젝트

<div align="center">

<sub>AX · Infra · Ops · Documentation</sub>

### [`ops-monitor`](https://github.com/yooneverse/ops-monitor)

**서비스 운영·장애 대응을 위한 AX 기반 인프라 프로젝트**

<br />

<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />

</div>

<br />

AI와 자동화 기능이 실제 서비스로 이어지기 위해서는 기능 구현뿐 아니라 실행 환경, 상태 점검, 장애 대응 흐름이 함께 필요하다는 점을 알게 되었습니다. 
이에 기술이 서비스 운영까지 연결되는 AX 흐름을 이해하기 위해, 이를 뒷받침하는 인프라 환경을 직접 구성했습니다.

Docker Compose 기반으로 FastAPI, PostgreSQL, Nginx를 연결하고  
서비스 상태 점검, 로그 확인, 장애 알림 흐름을 구성했습니다.

- API 및 DB Health Check
- Nginx 리버스 프록시 구성
- Discord 장애 알림
- 장애 상황 재현 및 로그 확인
- 트러블슈팅과 운영 과정 문서화
  
```mermaid
flowchart LR
    U["사용자 요청"] --> N["Nginx"]
    N --> A["FastAPI"]
    A --> D[("PostgreSQL")]

    H["Health Check"] --> A
    H --> D
    H --> W["Discord Alert"]

    classDef default fill:#F8FAFC,stroke:#94A3B8,color:#0F172A,stroke-width:1px;
    classDef point fill:#EFF6FF,stroke:#2563EB,color:#0F172A,stroke-width:1.5px;

    class U,H,W default;
    class N,A,D point;
```

> 상세 구조와 장애 대응 기록은 프로젝트 저장소에서 확인할 수 있습니다.

---

## 경험

<table>
  <tr>
    <td width="50%" valign="top">

### 카카오 장소 데이터 운영

* 15개월간 월 250건 이상의 장소 데이터 검토
* 폐업, 이전, 중복 등록, 카테고리 오류 확인
* 반복 오류를 11개 유형으로 분류
* 데이터 검토 기준과 처리 흐름 정리

  </td>
    <td width="50%" valign="top">

### 삼성 청년 SW·AI 아카데미

* 웹·모바일·AI 프로젝트 수행
* 팀장과 PM으로 일정·역할·산출물 관리
* 프론트엔드 개발 및 운영 참여
* **우수상** 선정 프로젝트 기획
* 최종 발표와 발표 자료 제작

  </td>
  </tr>
  <tr>
    <td width="50%" valign="top">

### [더 똑똑한 공원 길 찾기](https://seoulforest.letsee.io/)

* 제안자 겸 PL로서 시민 220여 명의 의견 수집 및 분류
* 서비스 기능과 안내 정보의 우선순위 설계
* **서울시 엠보팅 우수 제안 선정 (70% 이상 득표)**
* **6억 5천만 원 규모 사업 예산 확보**
* **서울시 시민참여예산제 우수 제안 선정**
* **서울특별시장상 창의상 수상**

  </td>
    <td width="50%" valign="top">

### 문화체육관광부 대학생 기자단

* 23명의 기사 주제와 취재 일정 관리
* 제출 현황 및 확인 사항 정리
* 일정 변경 공지와 진행 상황 공유
* 구성원별 후속 업무 조율
* **19기 선발 면접관 참여**

  </td>
  </tr>

</table>

---

## 기술 스택

### 인프라·운영

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
</p>

Docker Compose로 다중 컨테이너 환경을 구성하고, Nginx 요청 전달과 로그 기반 장애 확인을 경험했습니다.

### 백엔드·데이터베이스

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
</p>

API 요청·응답과 데이터 저장 흐름을 구현하고, 애플리케이션과 DB 연결 상태를 점검했습니다.

### 웹·모바일

<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=111827" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white" />
</p>

웹·모바일 UI를 구현하고 API 응답, 로딩, 오류 상태가 사용자 흐름과 연결되도록 구성했습니다.

### 협업·문서화

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white" />
  <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" />
</p>

일정과 역할, 화면 명세, API 명세를 공유해 팀이 같은 기준으로 작업할 수 있도록 관리했습니다.


<br />

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0891B2,50:2563EB,100:0F172A&height=3&section=footer" width="100%" />

<br />
<br />

<h3>김지윤</h3>

<p><strong>서비스 흐름 설계 · 프로젝트 운영 · 인프라</strong></p>

<a href="https://github.com/yooneverse">
  <img src="https://img.shields.io/badge/GitHub-yooneverse-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>
