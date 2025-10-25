<div align="center">

# 안녕하세요, 이해람입니다 👋

### Frontend Engineer | Product Maker

```typescript
const developer = {
  name: "이해람 (Haeram Lee)",
  role: "Frontend Lead",
  experience: "6+ years",
  philosophy: "사람을 위한 프로덕트를 만듭니다",
};
```

[![GitHub](https://img.shields.io/badge/GitHub-hetarho-181717?style=flat&logo=github)](https://github.com/hetarho)
[![Email](https://img.shields.io/badge/Email-sunlikeperson@gmail.com-EA4335?style=flat&logo=gmail)](mailto:sunlikeperson@gmail.com)

</div>

---

## 🧑‍💻 About Me

**6년 차, 사람을 위한 프로덕트를 만드는 프론트엔드 개발자입니다.**

저의 모든 실행 동기는 **사람에 대한 관심**에서 비롯됩니다.  
함께 일하는 동료와 실제 사용자의 경험을 개선하는 것에 집중합니다.

> _"개발도 사람이 하는 일, 프로덕트는 사용자를 위한 것"_

### 🎯 Core Values

- 🤝 **Developer Experience**: 팀원들의 생산성과 행복을 위한 개발 문화 조성
- 👥 **User Experience**: 현장 리서치를 통한 실사용자 중심의 제품 개선
- 🏗️ **Architecture**: 지속 가능하고 확장 가능한 코드베이스 설계

---

## 🏗️ Architecture Boilerplates

실무에서 경험한 아키텍처를 보일러플레이트로 정리해놓은 레포지토리입니다.

### 📦 Monorepo Boilerplate
[![Repo](https://img.shields.io/badge/Repository-blue?style=flat&logo=github)](https://github.com/hetarho/monorepo-boilerplate)

**Tech Stack:** `pnpm workspace` · `Turborepo` · `TypeScript` · `gRPC`

> 💡 **어떤 문제를 해결하나요?**  
> 
> React Web, Flutter Mobile, BFF Server, Backend Server를 하나의 레포지토리에서 관리하며, 효율적인 코드 공유와 타입 안정성을 보장합니다.
> 
> **실무 경험:**
> - 4개의 앱(React, Flutter, BFF, Backend)을 단일 레포에서 관리
> - gRPC/connect-rpc 기반 타입 안전한 통신
> - 공통 타입 정의를 패키지로 분리하여 중복 제거
> - pnpm workspace로 빠른 설치 및 효율적인 디스크 사용

<details>
<summary><b>주요 특징</b></summary>

- 📦 **패키지 구조**
  - `apps/web`: React 웹 애플리케이션
  - `apps/mobile`: Flutter 모바일 앱
  - `apps/bff`: Backend for Frontend 서버
  - `apps/backend`: 백엔드 API 서버
  - `packages/shared`: 공통 타입, 유틸리티
  - `packages/proto`: gRPC 프로토콜 정의

- ⚡ **빌드 최적화**
  - Turborepo 캐싱으로 빌드 시간 단축
  - 변경된 앱만 선택적 빌드
  - 병렬 빌드로 CI/CD 속도 향상

- 🔒 **타입 안정성**
  - 프로토콜 버퍼에서 TypeScript 타입 자동 생성
  - 공통 타입 패키지를 통한 일관된 데이터 구조
  - API 변경 시 컴파일 타임에 오류 감지

- 🛠️ **DX 개선**
  - 통합된 린팅/포매팅 설정
  - 단일 명령어로 모든 앱 실행
  - 의존성 버전 중앙 관리

</details>

---

### 🎨 FSD Architecture Boilerplate
[![Repo](https://img.shields.io/badge/Repository-Coming_Soon-gray?style=flat&logo=github)](https://github.com/hetarho)

**Tech Stack:** `React` · `TypeScript` · `FSD`

> 💡 **어떤 문제를 해결하나요?**  
> 도메인 중심 개발로 응집도 높은 코드를 작성합니다.

<details>
<summary><b>주요 특징</b></summary>

- 📁 **Layers**: app / pages / widgets / features / entities / shared
- 🔄 **Dependency Rule**: 하위 레이어만 참조 가능
- 🎯 **Feature-Sliced**: 기능별 독립적 개발 가능

</details>

---

### 🧱 Clean Architecture Boilerplate
[![Repo](https://img.shields.io/badge/Repository-Coming_Soon-gray?style=flat&logo=github)](https://github.com/hetarho)

**Tech Stack:** `TypeScript` · `Clean Architecture` · `DI Container`

> 💡 **어떤 문제를 해결하나요?**  
> 비즈니스 로직을 UI/프레임워크로부터 분리하여 테스트 가능하고 유지보수하기 쉬운 코드를 만듭니다.

<details>
<summary><b>주요 특징</b></summary>

- 🎯 **Domain**: 순수 비즈니스 로직
- 🔌 **Application**: 유즈케이스 구현
- 🌐 **Infrastructure**: 외부 의존성 (API, DB 등)
- 🖼️ **Presentation**: UI 레이어

</details>

---

## 🚀 Side Projects

개인적으로 진행 중인 사이드 프로젝트입니다.

### 🧠 Brain - 엔그램 기반 뇌과학 일기
[![Repo](https://img.shields.io/badge/Repository-blue?style=flat&logo=github)](https://github.com/hetarho/brain_diary)

**Tech Stack:** `Next.js 15` · `tRPC` · `Prisma` · `PostgreSQL` · `Gemini AI`

> 📝 **프로젝트 컨셉**  
> 
> 실제 뇌의 기억 처리 방식을 모방한 혁신적인 일기 애플리케이션입니다.  
> 일기를 뇌의 정보 처리 최소 단위인 **엔그램(Engram)**으로 분해하고,  
> 기억들 간의 복잡한 연결망을 시뮬레이션합니다.

<details>
<summary><b>주요 특징</b></summary>
**🔬 핵심 메커니즘:**

- 🧩 **Engram (엔그램)**: 기억의 원자
  - 일기를 의미 단위로 분해 (예: "카페에서 마신 커피", "비 오는 날의 풍경")
  - 시공간 맥락, 감정 톤, 기억 타입(에피소드/의미/절차) 등 속성 포함
  - 망각 곡선에 따라 시간이 지나면 자연스럽게 강도가 감소

- 🔗 **Synapse vs EngramLink**: 두 가지 연결 방식
  - **Synapse (시냅스)**: 물리적 연결 강도 - "얼마나 강하게 연결되어 있는가?"
  - **EngramLink**: 논리적 관계 - "왜 연결되어 있는가?" (시간적/공간적/인과적)

- 🏗️ **상호보완적 학습 시스템 (CLS)**
  - **HippocampusStore (해마)**: 새로운 경험을 즉각 저장하는 빠른 학습 시스템
  - **CortexStore (대뇌피질)**: 반복된 기억을 영구 저장하는 느린 학습 시스템

**🧪 뇌과학 이론 기반:**
- 헵의 규칙: "함께 발화하는 뉴런은 함께 연결된다"
- 에빙하우스 망각 곡선: 시간에 따른 기억 감소
- 기억 재공고화: 회상할 때마다 기억이 재구성됨
- 인코딩 특수성 원리: 맥락이 기억 인출의 단서가 됨

**💡 개발 배경 & 동기:**
- **기술적 도전**: 추상적인 뇌과학 이론을 실제 동작하는 소프트웨어로 구현
- **아키텍처 실험**: Layered Architecture로 LLM 엔진을 설계하여 관심사 분리
- **인간에 대한 탐구**: "기억이란 무엇인가?"에 대한 과학적 접근을 코드로 표현
- **배운 점**: 
  - 복잡한 도메인 모델링 (기억의 다차원적 속성 구조화)
  - tRPC를 활용한 타입 안전한 풀스택 개발
  - Gemini AI를 활용한 자연어 → 구조화된 데이터 변환
</details>
