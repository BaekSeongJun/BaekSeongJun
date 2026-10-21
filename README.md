# 👋 안녕하세요, Java 백엔드 개발자 백성준입니다.

**인증·인가와 서비스의 기본 구조를 단단하게 만드는 일**을 좋아합니다.
처음 보는 기술도 공식 문서부터 끝까지 읽고 직접 적용해 보며, 팀이 함께 일하는 규칙과 구조를 설계하는 것에 관심이 많습니다.
최근에는 **Claude Code** 같은 AI 코딩 도구를 팀 개발에 안전하게 쓰는 방법을 고민하고 있습니다.

<br>

## 🛠️ Tech Stacks

### Backend
<p>
  <img src="https://img.shields.io/badge/Java%2021-007396?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring%20Cloud%20Gateway-6DB33F?style=flat-square&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white"/>
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"/>
</p>

### Data
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
</p>

### Frontend
<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
</p>

### DevOps & Tools
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=claude&logoColor=white"/>
</p>

<br>

## 🚀 Projects

### 🎧 HelpNest · AI 고객상담(CS) 헬프데스크
`2026.09 – 2026.10` · 3인 팀 · 하이미디어아카데미 · [서비스](https://helpnest.kro.kr) · [docs](https://github.com/BaekSeongJun/helpnest-docs) · [back](https://github.com/BaekSeongJun/helpnest-back) · [front](https://github.com/BaekSeongJun/helpnest-front)

- **담당**: 인증/권한, 회원, 문의 접수, FAQ·답변 템플릿, 만족도 설문, 고객 이력, 공용 구조
- Spring Security + JWT 인증 (Access 30분 / Refresh 14일 httpOnly 쿠키, 프론트 자동 재발급)
- 역할 6종 × 엔드포인트 28개 = **168건**의 권한을 검사하는 `RoleAccessMatrixTest`
- 저장소 3개의 브랜치 전략·CODEOWNERS·PR 규칙과 팀 공용 `CLAUDE.md`, `git-commit` skill 작성 → 팀원 모두가 Claude Code로 개발하는 환경에서 서로의 코드를 지키는 협업 구조 설계

### 📚 BooksCamp · MSA 기반 온라인 서점
`2025.10 – 2025.12` · 8인 팀 · NHN Academy · [GitHub](https://github.com/nhnacademy-be11-bookscamp)

- **담당**: 회원 도메인과 인증·인가 전체
- Auth 서버의 JWT Access/Refresh Token 발급, Refresh Token은 Redis에 저장
- Spring Cloud Gateway에서 토큰 검증 및 자동 재발급, `@RequiredRole` 기반 인가
- Spring Security + Payco·Google OAuth2 로그인, 휴면 회원 전환 스케줄러

### 💊 우리동네약값 · 일반의약품 최저가 추천
`2026.09` · 1인 · 하이미디어아카데미 · [GitHub](https://github.com/BaekSeongJun/miniproject1)

- Python으로 공공데이터를 시드 데이터로 변환 (약국 23,571곳 · 약품 4,762종 · 가격 제보 약 376만 건)
- Spring Boot 4.1 + Next.js 16 + PostgreSQL 17 (`pg_trgm` 검색), PRD·DB·API 문서 직접 작성

<br>

## 🎓 Education & Certifications

- 충남대학교 컴퓨터공학과 학사 (2026.02)
- NHN Academy Java 백엔드 개발자 과정 수료 (2025.07 – 2026.01)
- 하이미디어아카데미 「자바와 생성형AI를 활용한 차세대 CRM플랫폼개발」 (2026.05 – 2026.11 수료 예정)
- SQLD (SQL 개발자) · OPIc IM2

<br>

## 📫 Contact

- **Email:** por9535@gmail.com
- **LinkedIn:** [seongjun-baek](https://www.linkedin.com/in/seongjun-baek-a509692b9/)

---
*맡은 시스템은 끝까지 책임지는 개발자가 되겠습니다.*
