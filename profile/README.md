# 📋 GitHub 업무 요청 및 관리 가이드

GitHub를 이용하여 **개발 요청, 수정·보완 요청 및 작업 진행 상황**을 관리합니다.

---

# 📚 사용 가이드

- 🆕 **[새로운 작업 등록 — Issue 작성 방법](./issue_guide.md)**
- 💬 **[진행 중인 작업 수정·보완 — Project 코멘트 작성 방법](./comment_guide.md)**

> ### 💡 어디에 작성해야 할지 모르겠다면?
>
> **이미 진행 중인 작업과 관련된 내용인가요?**
>
> **YES → [Project 코멘트](#현재-작업-중인-내용의-수정-및-보완)에 작성**  
> **NO → [새로운 Issue](#새로운-작업-요청)로 등록**
>
> **기본 원칙 : 기존 작업의 수정·보완은 Project 코멘트 / 새로운 작업은 Issue**

---

# 새로운 작업 요청

현재 진행 중인 작업과 관계없는 **새로운 업무**라면 해당 Repository의 **Issues**에 등록해주세요.

개발 관련 지식이 없어도 괜찮습니다.  
아래 표에서 요청하려는 내용과 가장 가까운 항목을 선택해주세요.

## 🗂️ 어떤 곳에 Issue를 등록해야 하나요?

| 요청 내용 | Repository | 예시 | 바로가기 |
|---|---|---|---|
| 🌐 **대시보드 / 웹 화면** | Frontend | 그래프, 버튼, 화면 디자인, 검색, 필터, UI | [➕ Issue 등록](https://github.com/kctenc/meerkat-dashboard-fe/issues/new/choose) |
| ⚙️ **서버 / 데이터** | Backend | 데이터 처리, API, DB, 서버 기능, 알람 로직 | [➕ Issue 등록](https://github.com/kctenc/meerkat-dashboard-be/issues/new/choose) |
| 📡 **센서 / 게이트웨이 통신** | TCP / Socket Server | 센서 데이터 수신, TCP 통신, 데이터 파싱 | [➕ Issue 등록](https://github.com/kctenc/meerkat-server-new-refactoring/issues/new/choose) |
| 📱 **모바일 앱** | Application | 앱 화면, Push 알림, 로그인, 모바일 기능 | [➕ Issue 등록](https://github.com/kctenc/meerkat_app/issues/new/choose) |

> 💡 **어디에 등록해야 할지 모르겠다면?**  
> 요청사항과 가장 관련 있어 보이는 Repository에 등록해주세요. 담당자가 확인 후 필요한 경우 적절한 작업으로 분류합니다.

👉 [📖 Issue 작성 방법 자세히 보기](./issue_guide.md)

---

# 📝 Repository별 상세 안내

## 🌐 프론트엔드 / 대시보드

사용자가 웹 브라우저에서 보는 **대시보드 화면 및 기능**과 관련된 요청입니다.

### 이런 작업을 등록해주세요.

- 그래프 표시 방법 변경
- 버튼 추가 및 변경
- 화면 디자인 수정
- 검색 기능 추가
- 필터 기능 추가
- 화면에 표시되는 내용 변경
- 대시보드 사용 편의성 개선

**예시**

> 현장 상세 화면의 센서 그래프에서 X축과 Y축을 선택해서 볼 수 있도록 해주세요.

👉 [Issues 목록 보기](https://github.com/kctenc/meerkat-dashboard-fe/issues)  
👉 **[➕ 새로운 Issue 등록하기](https://github.com/kctenc/meerkat-dashboard-fe/issues/new)**

---

## ⚙️ 백엔드 / 서버

화면에서 직접 보이지 않는 **서버 기능, 데이터 처리 및 API**와 관련된 요청입니다.

### 이런 작업을 등록해주세요.

- 데이터 처리 방식 변경
- API 기능 추가
- 데이터 저장 방식 변경
- DB 관련 작업
- 서버 기능 개선
- 알람 처리 로직 변경

**예시**

> 위험 단계 알람 발생 시 해당 알람 정보를 별도로 저장할 수 있도록 해주세요.

👉 [Issues 목록 보기](https://github.com/kctenc/meerkat-dashboard-be/issues)  
👉 **[➕ 새로운 Issue 등록하기](https://github.com/kctenc/meerkat-dashboard-be/issues/new)**

---

## 📡 TCP / Socket Server

센서 및 게이트웨이에서 서버로 데이터를 전달하는 **통신 및 데이터 수신**과 관련된 요청입니다.

### 이런 작업을 등록해주세요.

- 센서 데이터 수신 문제
- 게이트웨이 통신 문제
- TCP 연결 관련 문제
- 데이터 파싱 및 처리
- 수신 데이터 저장
- Socket Server 관련 기능

**예시**

> 게이트웨이에서 특정 센서 데이터가 전송됐는데 서버에서 수신되지 않는 문제가 있습니다.

👉 [Issues 목록 보기](https://github.com/kctenc/meerkat-server-new-refactoring/issues)  
👉 **[➕ 새로운 Issue 등록하기](https://github.com/kctenc/meerkat-server-new-refactoring/issues/new)**

---

## 📱 모바일 애플리케이션

Android / iOS **모바일 앱 화면 및 기능**과 관련된 요청입니다.

### 이런 작업을 등록해주세요.

- 앱 화면 수정
- 로그인 기능
- Push 알림
- 센서 데이터 확인 기능
- 모바일 UI 개선
- 앱에서 발생하는 오류

**예시**

> 위험 알람 Push를 눌렀을 때 해당 현장 화면으로 바로 이동할 수 있도록 해주세요.

👉 [Issues 목록 보기](https://github.com/kctenc/meerkat_app/issues)  
👉 **[➕ 새로운 Issue 등록하기](https://github.com/kctenc/meerkat_app/issues/new)**

---

# 현재 작업 중인 내용의 수정 및 보완

이미 **GitHub Projects에서 진행 중인 작업**과 관련된 내용이라면 새로운 Issue를 만들지 않고 **해당 작업의 코멘트(Comment)**에 작성해주세요.

### 다음과 같은 경우입니다.

- 현재 개발 중인 기능의 수정 요청
- 작업 중인 화면의 디자인 변경
- 기존 요청사항에 내용 추가
- 개발 결과 확인 후 수정 요청
- 테스트 후 발견된 보완사항
- 기존 작업에 대한 추가 설명이나 자료 전달

👉 [📖 Project 코멘트 작성 방법](./comment_guide.md)

### 예시

현재 아래 작업이 진행 중이라고 가정합니다.

> `대시보드 그래프 X/Y축 선택 기능 추가`

작업 진행 중 다음과 같은 요청이 추가되었습니다.

> X/Y축 선택 기능 확인했습니다.  
> 추가로 마지막에 선택했던 축이 유지되도록 수정 부탁드립니다.

이 경우 새로운 Issue를 생성하지 않고 **기존 작업의 코멘트에 추가 요청사항을 작성**합니다.

---

# ✅ 업무 요청 흐름

### 🆕 새로운 작업

`새로운 요청 발생`  
↓  
`관련 Repository 선택`  
↓  
`Issue 등록`  
↓  
`담당자 확인`  
↓  
`Project에서 작업 진행`

### 💬 진행 중인 작업의 수정·보완

`수정 또는 보완사항 발생`  
↓  
`GitHub Projects 이동`  
↓  
`진행 중인 작업 선택`  
↓  
`Comment 작성`  
↓  
`담당자 확인`

---

> ### 📌 꼭 확인해주세요
>
> 업무 요청 내용을 메신저나 구두로만 전달하면 작업 내용이나 변경 이력을 확인하기 어렵습니다.
>
> 가능한 모든 개발 요청은 **GitHub Issue 또는 Project 코멘트에 기록**해주세요.
>
> **🆕 새로운 작업 → Issue**  
> **💬 진행 중인 작업의 수정·보완 → Project Comment**
