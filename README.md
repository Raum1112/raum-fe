# 0. 프로젝트 목차 (Table of Contents)

### 1. **서비스 개요 (Service Overview)**

1-1. [서비스 개요 (Service Overview)](#1-1-서비스-개요-service-overview)  
1-2. [프로젝트 설명 (Project Description)](#1-2-프로젝트-설명-project-description)

<!-- 1-3. [데모 (Demo)](#1-3-데모-demo)
1-4. [설치 방법 (Installation)](#1-4-설치-방법-installation)
1-5. [사용 방법 (Usage)](#1-5-사용-방법-usage) -->

### 2. **기능 및 설계 (Features & Design)**

2-1. [기능 목록 (Features)](#2-1-기능-목록-features)  
2-2. [와이어프레임 (Wireframes)](#2-2-와이어프레임-wireframes)  
2-3. [ERD (Entity Relationship Diagram)](#2-3-erd-entity-relationship-diagram)

<!-- 2-4. [서비스 아키텍처 (Service Architecture)](#2-4-서비스-아키텍처-service-architecture)   -->

### 3. **기술 스택 (Tech Stack)**

3-1. [기술 스택 (Tech Stack)](#3-1-기술-스택-tech-stack)

### 4. **기획 및 전략 (Planning & Strategy)**

4-1. [기획 (Planning)](#4-1-기획-planning)  
4-2. [문제 정의 (Problem Definition)](#4-2-문제-정의-problem-definition)  
4-3. [서비스 목표 (Service Goals)](#4-3-서비스-목표-service-goals)

### 5. **MVP (Minimum Viable Product)**

5-1. [MVP 정의 (MVP Definition)](#5-1-mvp-정의-mvp-definition)  
5-2. [MVP 기술 스택 선택 (MVP Tech Stack Selection)](#5-2-mvp-기술-스택-선택-mvp-tech-stack-selection)  
5-3. [MVP 개선 로드맵 (MVP Improvement Roadmap)](#5-3-mvp-개선-로드맵-mvp-improvement-roadmap)

### 6. **기타 (Miscellaneous)**

6-1. [역할 (Authors and Roles)](#6-1-역할-authors-and-roles)  
6-2. [라이센스 (License)](#7-1-라이센스-license)

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

## 1-2. 프로젝트 설명 (Project Description)

<!-- 이 프로젝트는 **[문제 설명]**을 해결하기 위한 서비스입니다.
[구체적인 문제 해결 방법 및 제공하는 가치 설명] -->

RAUM은 남성 입문자들이 스킨케어를 시작하는 데 필요한 맞춤형 가이드를 제공합니다.

본 서비스는 4가지 주요 기능을 통해 사용자의 피부를 분석하고, 그에 맞는 제품 추천과 최적의 사용 순서를 자동으로 제시합니다.

- 피부 타입 진단: 간단하지만 핵심적인 질문들로 구성된 설문을 통해 사용자의 피부 타입을 진단합니다.

- 개인화된 레포트 제공: 설문으로 진단한 피부 타입을 바탕으로, 사용자의 피부 상태와 고민을 분석한 맞춤형 리포트를 제공합니다.

- 제품 추천: 분석 결과를 바탕으로 AI가 사용자에게 가장 적합한 스킨케어 제품을 추천합니다.

- 루틴 최적화: 제품을 선택한 후, AI가 아침/저녁 사용 순서를 최적화하여 루틴을 자동으로 생성하고, 제품 간 시너지 효과 및 충돌 정보를 제공하여 최적의 스킨케어 조합을 안내합니다.

<br/><br/>

# 2. 기능 및 설계 (Features & Design)

## 2-1. 기능 목록 (Features)

<!-- - 기능 1: [기능 설명]
- 기능 2: [기능 설명]
- 기능 3: [기능 설명] -->

<table border="1" cellpadding="10" cellspacing="0" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center;">기능명</th>
      <th style="text-align: center;">기능 설명</th>
      <th style="text-align: center;">중요도</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>간단한 피부 타입 진단</td>
      <td>사용자가 5~6개의 질문에 답하여 피부 타입을 빠르게 진단할 수 있도록 돕는 기능입니다. AI가 사용자의 기본 피부 타입을 예측합니다.</td>
      <td>매우 중요</td>
    </tr>
    <tr>
      <td>심층 설문을 통한 개인별 피부 분석</td>
      <td>회원 가입 후 심층 설문을 통해 구체적인 피부 고민과 생활 습관을 수집하여 개인화된 피부 분석 레포트를 제공합니다.</td>
      <td>중요</td>
    </tr>
    <tr>
      <td>맞춤형 제품 추천</td>
      <td>AI가 사용자의 피부 타입과 고민에 맞춰 최적화된 스킨케어 제품을 추천하는 기능입니다. 성분 기반의 추천 알고리즘을 사용합니다.</td>
      <td>매우 중요</td>
    </tr>
    <tr>
      <td>스킨케어 루틴 생성 및 시너지 분석</td>
      <td>사용자에게 최적화된 아침/저녁 루틴을 자동으로 생성하고, 제품 간 시너지 효과 및 충돌 정보를 제공하여 효과적인 사용 순서를 안내합니다.</td>
      <td>매우 중요</td>
    </tr>
    <tr>
      <td>회원가입</td>
      <td>사용자가 개인 계정을 생성하여 서비스를 이용할 수 있도록 하는 기능입니다. 기본적인 사용자 정보를 입력하고 회원가입을 진행합니다.</td>
      <td>매우 중요</td>
    </tr>
    <tr>
      <td>로그인</td>
      <td>회원가입 후, 사용자가 자신의 계정에 로그인하여 개인화된 서비스를 이용할 수 있는 기능입니다.</td>
      <td>매우 중요</td>
    </tr>
    <tr>
      <td>마이페이지</td>
      <td>사용자가 자신의 프로필, 피부 타입, 추천 받은 제품, 루틴 등을 확인하고 수정할 수 있는 개인화된 페이지입니다.</td>
      <td>중요</td>
    </tr>
    <tr>
      <td>비밀번호 찾기</td>
      <td>사용자가 비밀번호를 잊어버린 경우, 이메일 등을 통해 비밀번호를 재설정할 수 있는 기능입니다.</td>
      <td>중요</td>
    </tr>
    <tr>
      <td>로그아웃</td>
      <td>사용자가 자신의 계정에서 로그아웃하여 서비스를 종료할 수 있도록 하는 기능입니다.</td>
      <td>보통</td>
    </tr>
  </tbody>
</table>

## 2-2. 와이어프레임 (Wireframes)

<!-- **와이어프레임**
- ![Wireframe Image](wireframe.png)
- [와이어프레임 설명] -->

### 로그인, 회원가입

![로그인, 회원가입 페이지](/readme_images/wireframe/로그인,%20회원가입.png)

### 간단 설문

![간단 설문 진행 및 결과 페이지](/readme_images/wireframe/간단%20설문%20진행%20및%20결과.png)

### 심층 설문

![심층 설문 진행 페이지](/readme_images/wireframe/심층%20설문%20진행.png)
![심층 설문 결과 페이지](/readme_images/wireframe/심층%20설문%20결과.png)

### 맞춤 제품 추천 및 마이 루틴 편집

![기타 페이지](/readme_images/wireframe/기타%20페이지.png)

## 2-3. ERD (Entity Relationship Diagram)

<!-- **ERD 다이어그램**
- ![ERD Diagram](erd.png)
- [ERD 설명] -->

![ERD Diagram](/readme_images/ERD.png)

<!-- ## 2-4. 서비스 아키텍처 (Service Architecture) -->

<!-- **서비스 아키텍처 다이어그램**
- ![Architecture Diagram](architecture.png)
- [API 구조 및 서비스 흐름 설명] -->

<br/><br/>

# 3. 기술 스택 (Tech Stack)

## 3-1. 기술 스택 (Tech Stack)

<!-- - **백엔드**: [백엔드 기술 스택]
- **프론트엔드**: [프론트엔드 기술 스택]
- **AI**: [AI 기술 스택] -->

### 💻 Backend

|    카테고리    | 기술 스택           | 사용 목적                                |
| :------------: | :------------------ | :--------------------------------------- | ------------------------------------------- | --- |
| **주요 언어**  | **Java** (JDK 17)   | 안정적인 비즈니스 로직 구현 및 서버 개발 |
| **프레임워크** | **Spring Boot 3.x** | RESTful API 구축 및 개발 생산성 향상     |
|      <!--      | **데이터베이스**    | **MySQL** / **Redis**                    | 영속적 데이터 관리 / 고속 캐싱 및 세션 관리 | --> |
|      <!--      | **API 통신**        | **RESTful API**                          | 클라이언트와의 표준 통신 규약 채택          | --> |

### 🎨 Frontend

|    카테고리    | 기술 스택        | 사용 목적                                              |
| :------------: | :--------------- | :----------------------------------------------------- | ------------------------------------------- | --- |
| **프레임워크** | **React Native** | 컴포넌트 기반 iOS와 Android 앱을 위한 네이티브 앱 개발 |
|      <!--      | **상태 관리**    | **[Redux / Recoil 등]**                                | 전역 상태 관리 및 효율적인 데이터 흐름 제어 | --> |
|      <!--      | **스타일링**     | **[Styled Components / Tailwind CSS 등]**              | 컴포넌트 별 스타일링 및 디자인 시스템 구축  | --> |
|      <!--      | **배포 환경**    | **[Vercel / Netlify 등]**                              | 빠른 배포 자동화 및 호스팅                  | --> |

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

<br/>

## 4-2. 문제 정의 (Problem Definition)

<!-- - **현재 문제**: [현재 해결해야 하는 문제]
- **문제의 중요성**: [문제가 중요한 이유]
- **기존 해결책**: [기존 해결책의 한계] -->

최근 '그루밍족'이라는 용어가 보편화될 만큼, 남성의 외모 관리에 대한 관심이 폭발적으로 증가하고 있습니다. 일상 속 피부 트러블, 면도 후 자극, 피부 톤 개선 등 남성들의 구체적인 스킨케어 니즈(Needs)는 분명하게 존재합니다.
그러나 현재 시장은 이러한 수요를 제대로 뒷받침하지 못하고 있습니다.
남성 사용자들은 수많은 제품과 광고성 정보의 홍수 속에서 "정말 나에게 맞는 제품이 무엇인가?"라는 근본적인 어려움을 겪고 있습니다. 특히 스킨케어 입문자일수록 다음과 같은 명확한 문제점(Pain Point)에 직면합니다.

1. **정보 과부하**: 무엇부터 시작해야 할지 모를 만큼 정보가 너무 많습니다.

2. **신뢰도 부족**: 대부분의 정보가 광고성이거나 과장되어 신뢰하기 어렵습니다.

3. **개인화 부재**: 자신의 피부 타입과 라이프스타일에 제품이 맞는지 확인할 방법이 불명확합니다.

<br/>

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

<br/><br/>

# 5. MVP (Minimum Viable Product)

## 5-1. MVP 정의 (MVP Definition)

<!-- **MVP 정의**
- **목표**: [MVP의 목표와 핵심 가치]
- **핵심 기능 선정**: [MVP에 포함될 핵심 기능들] -->

MVP의 주요 목표는 스킨케어 입문자들이 복잡한 스킨케어 정보를 손쉽게 접근하고, 자신에게 맞는 제품을 추천받을 수 있도록 돕는 것입니다. 해커톤 기간 내에 구현할 MVP의 주요 목표는 다음과 같습니다:

1. 간단한 설문을 통해 피부 타입을 진단 및 시각화할 수 있는 기능

2. 피부 타입에 맞는 개인 맞춤형 제품을 추천하는 기능

3. 기본적인 스킨케어 루틴을 제시하는 기능

4. 회원 관리 기능 (사용자 등록 및 로그인)

## 5-2. MVP 기술 스택 선택 (MVP Tech Stack Selection)

<!-- **MVP 기술 스택**
- [MVP에 필요한 최소한의 기술 스택] -->

프론트엔드: React Native (모바일 웹 및 앱을 위한 UI 구현)

백엔드: Spring Boot (서버 구축)

<!-- AI 모델: LightGBM, RandomForest (피부 타입 분류), 콘텐츠 기반 추천 시스템 -->

<!-- DB: MongoDB (사용자 데이터, 제품 정보, 설문 응답 저장) -->

## 5-3. MVP 개선 로드맵 (MVP Improvement Roadmap)

<!-- **MVP 개선 로드맵**
- [MVP 개선을 위한 로드맵과 버전업 전략] -->

### 1. MVP 출시 후 첫 번째 단계: 기본 기능 안정화

- 목표: MVP에서 제공하는 핵심 기능을 안정화하고 초기 사용자 피드백을 반영하여 제품의 품질을 개선

- 핵심 작업:

  회원 관리 기능 개선: 로그인/회원가입 과정에서 발생할 수 있는 오류 수정 및 안정성 확보.

  피부 타입 진단 정확도 향상: 간단한 설문 결과를 기반으로 한 피부 타입 분류 모델의 성능 향상.

  UI/UX 개선: 사용자가 쉽게 이해하고 사용할 수 있도록 직관적인 UI/UX 개선.

  사용자 피드백 수집: 초기 사용자 피드백을 수집하여 어떤 기능이나 부분에서 불편함을 느꼈는지 파악.

- 목표 성과: 안정적이고 오류가 적은 사용자 경험 제공.

### 2. 두 번째 단계: 개인화 및 추천 알고리즘 개선

- 목표: 제품 추천 기능을 개선하여 보다 개인화된 추천을 제공하고, 추천 알고리즘의 정확도를 높이기

- 핵심 작업:

  심층 설문 추가: 사용자의 피부 고민(예: 트러블, 민감성 등), 생활 습관(예: 면도 주기, 자외선 노출)을 더 구체적으로 반영하는 심층 설문 기능 추가.

  추천 알고리즘 고도화: 추천 알고리즘을 고도화하여 피부 타입, 고민, 제품의 성분 등을 더 잘 반영할 수 있도록 개선.

  루틴 최적화 모델: 제품 추천 외에도 사용자가 보유한 제품을 활용한 최적의 루틴을 자동 생성하는 기능 추가.

  시너지 분석: 추천된 제품 간의 시너지 효과(예: 보습 극대화)나 충돌 정보(예: 주의 성분 조합) 제공 기능 추가.

- 목표 성과:

  더욱 정확한 개인 맞춤형 제품 추천 제공.

  루틴 생성 및 시너지 분석 기능으로 사용자가 최적의 스킨케어 루틴을 쉽게 설정할 수 있도록 지원.

### 3. 세 번째 단계: 상호작용 및 피드백 기반 개선

- 목표: 사용자의 행동을 반영한 지속적인 제품 개선과 사용자 맞춤형 서비스를 제공

- 핵심 작업:

  사용자 피드백 반영: 제품 사용 후 만족도, 자극 여부 등 사용자 피드백을 반영하여 추천 알고리즘을 개선.

  추천 시스템 지속적 학습: 사용자 피드백(만족도 등)을 바탕으로 AI 모델이 지속적으로 학습하여 추천의 정확도를 높이는 시스템 구축.

  알림 기능 추가: 사용자가 스킨케어 루틴을 놓치지 않도록 알림 기능 추가.

- 목표 성과:

  사용자 피드백을 반영하여 제품 추천의 신뢰성과 정확도를 높임.

  사용자 경험을 강화하고, 맞춤형 솔루션을 제공하여 사용자 만족도 증가.

<br/><br/>

# 6. 기타 (Miscellaneous)

## 6-1. 라이센스 (License)

<!-- **라이센스 종류**
- [라이센스 상세 내용] -->

```
The MIT License (MIT)

Copyright (c) <year> <copyright holders>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

## 6-2. 역할 (Authors and Roles)

<!-- **저자 및 기여자**
- [기여자 이름 및 역할] -->

<div align="center">

|                                       🥇 팀장                                        |                                           💡 팀원                                            |                                       💻 팀원                                        |
| :----------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------: |
| [![손수창 깃허브](https://github.com/sonsuchang.png)](https://github.com/sonsuchang) | [![윤승혁 깃허브](https://github.com/SeungHyeokYoon.png)](https://github.com/SeungHyeokYoon) | [![이다빈 깃허브](https://github.com/dabinchiii.png)](https://github.com/dabinchiii) |
|                     **[손수창](https://github.com/sonsuchang)**                      |                       **[윤승혁](https://github.com/SeungHyeokYoon)**                        |                     **[이다빈](https://github.com/dabinchiii)**                      |
|                             `Java, Spring, Python, AWS`                              |                                     `Java, Spring, AWS`                                      |                                    `React Native`                                    |

<!-- todo: 세부 역할 추가하기 -->

</div>
