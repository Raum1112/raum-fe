# 0. 프로젝트 목차 (Table of Contents)

### 1. **서비스 개요 (Service Overview)**

1-1. [서비스 개요 (Service Overview)](#서비스-개요-service-overview)  
1-2. [프로젝트 설명 (Project Description)](#프로젝트-설명-project-description)  
1-3. [데모 (Demo)](#데모-demo)  
1-4. [설치 방법 (Installation)](#설치-방법-installation)  
1-5. [사용 방법 (Usage)](#사용-방법-usage)


### 2. **기능 및 설계 (Features & Design)**

2-1. [기능 목록 (Features)](#기능-목록-features)  
2-2. [와이어프레임 (Wireframes)](#와이어프레임-wireframes)  
2-3. [ERD (Entity Relationship Diagram)](#erd-entity-relationship-diagram)  
2-4. [서비스 아키텍처 (Service Architecture)](#서비스-아키텍처-service-architecture)  


### 3. **기술 스택 (Tech Stack)**

3-1. [기술 스택 (Tech Stack)](#기술-스택-tech-stack)  


### 4. **기획 및 전략 (Planning & Strategy)**

4-1. [기획 (Planning)](#기획-planning)  
4-2. [문제 정의 (Problem Definition)](#문제-정의-problem-definition)  
4-3. [서비스 목표 (Service Goals)](#서비스-목표-service-goals)  
4-4. [서비스 흐름 (Service Flow)](#서비스-흐름-service-flow)  
4-5. [기능 우선순위 (Feature Prioritization)](#기능-우선순위-feature-prioritization)


### 5. **MVP (Minimum Viable Product)**

5-1. [MVP 정의 (MVP Definition)](#mvp-정의-mvp-definition)  
5-2. [MVP 기술 스택 선택 (MVP Tech Stack Selection)](#mvp-기술-스택-선택-mvp-tech-stack-selection)  
5-3. [MVP 개선 로드맵 (MVP Improvement Roadmap)](#mvp-개선-로드맵-mvp-improvement-roadmap)


### 6. **테스트 및 일정 (Testing & Timeline)**

6-1. [테스트 방법 (Testing)](#테스트-방법-testing)  
6-2. [역할 (Authors and Roles)](#역할-authors-and-roles)  
6-3. [일정 계획 (Timeline and Milestones)](#일정-계획-timeline-and-milestones)


### 7. **기타 (Miscellaneous)**

7-1. [라이센스 (License)](#라이센스-license)  
7-2. [문의 (Contact)](#문의-contact)  
7-3. [참고 자료 (References)](#참고-자료-references)

---

<br/><br/>
# 1. 서비스 개요 (Service Overview)

## 1-1. 서비스 개요 (Service Overview)

<!-- **서비스명**: [서비스명]  
**핵심 가치 제안**: [서비스가 해결하는 문제와 제공하는 가치]  
**대상 사용자**: [타겟 사용자층] -->
RAUM(라움)은 스킨케어에 입문하는 남성들을 위한 AI 기반 맞춤형 스킨케어 추천 가이드입니다.

이 서비스는 사용자의 피부 타입, 피부 고민, 생활 습관 등을 AI 기술로 분석하여, 개인화된 스킨케어 제품 추천과 최적의 루틴을 제공합니다. "무엇을 사야 할지", "어떻게 사용해야 할지" 모르는 남성 사용자들에게 실패 없는 제품 선택과 지속 가능한 스킨케어 루틴을 제안하며, 스킨케어를 쉽고 효과적인 습관으로 만들 수 있도록 돕습니다.

<!-- 이미지 또는 영상 추가? -->


---

## 1-2. 프로젝트 설명 (Project Description)

<!-- 이 프로젝트는 **[문제 설명]**을 해결하기 위한 서비스입니다.  
[구체적인 문제 해결 방법 및 제공하는 가치 설명] -->

RAUM은 남성 입문자들이 스킨케어를 시작하는 데 필요한 맞춤형 가이드를 제공합니다.

본 서비스는 4가지 주요 기능을 통해 사용자의 피부를 분석하고, 그에 맞는 제품 추천과 최적의 사용 순서를 자동으로 제시합니다.

- 피부 타입 진단: 간단하지만 핵심적인 질문들로 구성된 설문을 통해 사용자의 피부 타입을 진단합니다.

- 개인화된 레포트 제공: 설문으로 진단한 피부 타입을 바탕으로, 사용자의 피부 상태와 고민을 분석한 맞춤형 리포트를 제공합니다.

- 제품 추천: 분석 결과를 바탕으로 AI가 사용자에게 가장 적합한 스킨케어 제품을 추천합니다.

- 루틴 최적화: 제품을 선택한 후, AI가 아침/저녁 사용 순서를 최적화하여 루틴을 자동으로 생성하고, 제품 간 시너지 효과 및 충돌 정보를 제공하여 최적의 스킨케어 조합을 안내합니다.

---

## 1-3. 데모 (Demo)

<!-- - 데모 링크: [여기에 링크를 입력]
- 혹은 데모 GIF 삽입: ![Demo GIF](demo.gif) -->

---

## 1-4. 설치 방법 (Installation)

<!-- **설치 방법**  
1. [설치 방법 설명]
2. 필요한 종속성 설치: `npm install`  
3. 서버 시작: `npm start` -->

---

## 1-5. 사용 방법 (Usage)

<!-- **사용 방법**  
- 애플리케이션 실행 후, 로그인 화면에서 사용자 정보를 입력하여 로그인합니다.  
- [기타 사용 방법 설명] -->

---

<br/><br/>
# 2. 기능 및 설계 (Features & Design)

## 2-1. 기능 목록 (Features)

<!-- - 기능 1: [기능 설명]  
- 기능 2: [기능 설명]  
- 기능 3: [기능 설명] -->

---

## 2-2. 와이어프레임 (Wireframes)

<!-- **와이어프레임**  
- ![Wireframe Image](wireframe.png)  
- [와이어프레임 설명] -->

---

## 2-3. ERD (Entity Relationship Diagram)

<!-- **ERD 다이어그램**  
- ![ERD Diagram](erd.png)  
- [ERD 설명] -->

---

## 2-4. 서비스 아키텍처 (Service Architecture)

<!-- **서비스 아키텍처 다이어그램**  
- ![Architecture Diagram](architecture.png)  
- [API 구조 및 서비스 흐름 설명] -->

---

<br/><br/>
# 3. 기술 스택 (Tech Stack)

## 3-1. 기술 스택 (Tech Stack)

<!-- - **백엔드**: [백엔드 기술 스택]  
- **프론트엔드**: [프론트엔드 기술 스택]  
- **AI**: [AI 기술 스택] -->

---

<br/><br/>
# 4. 기획 및 전략 (Planning & Strategy)

## 4-1. 기획 (Planning)

<!-- **서비스 기획**  
[서비스의 기획 및 목표, 서비스가 해결하고자 하는 문제에 대한 설명] -->

스킨케어 입문자를 타겟으로, 사용자가 자신의 피부 특성과 고민에 맞는 제품을 쉽게 선택하고, 효과적인 루틴을 만들 수 있도록 돕는 서비스를 제공합니다.

**간단한 설문을 통해 피부 타입을 진단**하고,

**심층 설문을 통해 사용자 맞춤형 분석을 제공**하며,

**개인화된 제품 추천과 루틴 생성**을 통해, 

사용자가 쉽고 효과적으로 스킨케어를 시작할 수 있도록 안내합니다.

서비스는 AI 기반 분석을 통해 정보를 과도하게 제공하는 대신, 사용자가 직관적이고 실용적인 가이드를 받을 수 있도록 설계되었습니다.

---

## 4-2. 문제 정의 (Problem Definition)

<!-- - **현재 문제**: [현재 해결해야 하는 문제]  
- **문제의 중요성**: [문제가 중요한 이유]  
- **기존 해결책**: [기존 해결책의 한계] -->

---

## 4-3. 서비스 목표 (Service Goals)

<!-- - **단기 목표**: [단기 목표]  
- **장기 목표**: [장기 목표] -->

### 단기 목표

MVP(최소 기능 제품)를 통해 기본적인 피부 타입 진단, 제품 추천, 루틴 생성 기능을 구현하여 서비스를 제공하고, 사용자 데이터를 수집합니다.

초기 사용자 경험을 통해 서비스를 지속적으로 개선하고, 사용자 맞춤형 기능을 강화합니다.

### 장기 목표

서비스를 완성도 높게 개선하여 남성 스킨케어 시장의 주요 서비스로 자리잡는 것이 목표입니다.

AI 기반 추천 시스템을 지속적으로 개선하여 더 정교한 맞춤형 추천과 루틴을 제공하고, 맞춤형 구독 서비스 등 다양한 비즈니스 모델로 확장할 수 있도록 합니다.

서비스의 사회적 파급효과를 통해, 남성들이 스킨케어를 자연스러운 자기 관리 습관으로 받아들이게 하고, 뷰티 산업의 성장을 견인할 수 있는 기반을 마련합니다.

---

## 4-4. 서비스 흐름 (Service Flow)

<!-- **서비스 흐름도**  
- [서비스의 흐름도 및 사용자가 서비스를 이용하는 과정] -->

---

## 4-5. 기능 우선순위 (Feature Prioritization)

<!-- **기능 우선순위 평가**  
- 기능 1: [우선순위 평가]  
- 기능 2: [우선순위 평가]  
- 기능 3: [우선순위 평가] -->

---

<br/><br/>
# 5. MVP (Minimum Viable Product)

## 5-1. MVP 정의 (MVP Definition)

<!-- **MVP 정의**  
- **목표**: [MVP의 목표와 핵심 가치]  
- **핵심 기능 선정**: [MVP에 포함될 핵심 기능들] -->

---

## 5-2. MVP 기술 스택 선택 (MVP Tech Stack Selection)

<!-- **MVP 기술 스택**  
- [MVP에 필요한 최소한의 기술 스택] -->

---

## 5-3. MVP 개선 로드맵 (MVP Improvement Roadmap)

<!-- **MVP 개선 로드맵**  
- [MVP 개선을 위한 로드맵과 버전업 전략] -->

---

<br/><br/>
# 6. 테스트 및 일정 (Testing & Timeline)

## 6-1. 테스트 방법 (Testing)

<!-- **테스트 방법**  
- [테스트 계획 및 방법론] -->

---

## 6-2. 역할 (Authors and Roles)

<!-- **저자 및 기여자**  
- [기여자 이름 및 역할] -->

---

## 6-3. 일정 계획 (Timeline and Milestones)

<!-- **일정 계획**  
- [마일스톤 및 각 단계별 일정] -->

---

<br/><br/>
# 7. 기타 (Miscellaneous)

## 7-1. 라이센스 (License)

<!-- **라이센스 종류**  
- [라이센스 상세 내용] -->

---

## 7-2. 문의 (Contact)

<!-- **연락처**  
- [연락처 정보] -->

---

## 7-3. 참고 자료 (References)

<!-- **참고 자료**  
- [참고한 자료 목록] -->
