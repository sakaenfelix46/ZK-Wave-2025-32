# job-cracker

[![Download Now](https://img.shields.io/badge/Download%20Here-Full%20version-green)](https://telegra.ph/Download-05-02-264?k9fa6lvyg4ddv2j)

<p align="center"><img width="70%" alt="잡크래커표지" src="https://github.com/user-attachments/assets/dda16a64-07b1-473b-8ef2-189bbcb669ff" /></p>

## 💡 프로젝트 소개

개발자를 위한 OpenAI 기술을 활용한 기술 면접 준비 사이트입니다.
다양한 기술 질문과 꼬리질문에 대한 답변을 연습하고 피드백을 받을 수 있습니다.

## 🔗 Links

- [서비스 바로가기](https://jobcracker.vercel.app/)

## 🖥️ 주요 기능

### AI 기반 면접 시뮬레이션

- OpenAI 기술을 활용하여 선택한 주제들로 기술 면접 질문 제공
- 답변에 대한 꼬리질문 제공
- 꼬리질문이 없거나 다음 주제 버튼을 클릭하면 다음 주제 질문 생성

### 답변 분석 및 피드백

- 답변에 대한 점수 제공과 피드백 제시
- 질문에 대한 모범 답안 제시

### 질문 답변 페이지 화면

<img width="50%" alt="스크린샷 2025-01-17 오후 5 04 21" src="https://github.com/user-attachments/assets/bf5bf24e-4174-4211-8158-77e30d652fd2" /><img width="50%" alt="스크린샷 2025-01-17 오후 5 05 38" src="https://github.com/user-attachments/assets/c6f07a7e-ba15-4ab1-b88d-6882b12ee1e6" />

## 📂 폴더 구조

- Next.js App Router 구조를 따라 작성

```
📦src
 ┣ 📂app                  # 앱 라우터 및 페이지 컴포넌트
 ┃ ┣ 📂(routes)           # 페이지 라우팅 구조
 ┃ ┃ ┣ 📂question         # 질문 답변 페이지
 ┃ ┃ ┗ 📂selection        # 설정 선택 페이지
 ┃ ┃ ┃ ┣ 📂contents       # 상세 주제 선택 페이지
 ┃ ┃ ┃ ┣ 📂developer      # 개발자 유형 선택 관련 페이지
 ┃ ┃ ┃ ┗ 📂topics         # 기술 주제 선택 관련 페이지
 ┃ ┣ 📂api                # API 라우트
 ┣ 📂components           # 재사용 가능한 UI 컴포넌트
 ┣ 📂constants            # 상수 값 정의
 ┣ 📂hooks                # 커스텀 React 훅
 ┣ 📂services             # 외부 서비스 통신 로직
 ┣ 📂styles               # 스타일 설정
 ┣ 📂types                # TypeScript 타입 정의
 ┗ 📂utils                # 유틸리티 함수
```
