# 🕹️ 리그 오브 레전드(LoL) 웹 UI/UX 개선 미니 프로젝트

## 1. 프로젝트 개요
본 프로젝트는 **리그 오브 레전드(LoL) 공식 웹사이트의 UI/UX를 개선**하여  
사용자가 원하는 정보를 **더 빠르고 직관적으로 탐색**할 수 있도록 재설계한 미니 프로젝트입니다.

> 핵심 목표: **“한눈에 보이는 정보 중심 UX”**

url: https://junhongkim95.github.io/LGE_DXSchool_miniProject_LoL_Web/

---

## 2. 문제 정의 (Why)

현재 LoL 웹사이트는 정보의 양은 많지만,  
**사용자 관점에서 정보 접근성과 가독성이 낮은 구조**를 가지고 있습니다.

### 🔎 주요 문제점

#### 🏠 메인 페이지
- <details>
  <summary><b>기존 웹사이트 화면</b> (클릭해서 펼치기)</summary>
  https://www.leagueoflegends.com/ko-kr/

</details>


- 유사한 성격의 콘텐츠가 중복 노출됨
- 사용자의 티어 정보 확인을 위해 **클라이언트에 접속하거나**
  OP.GG, FOW 등 **외부 사이트에 의존해야 하는 불편함** 존재

#### 📄 패치 노트 페이지
- <details>
  <summary><b>기존 웹사이트 화면</b> (클릭해서 펼치기)</summary>
  https://www.leagueoflegends.com/ko-kr/news/game-updates/patch-26-1-notes/


</details>

- 텍스트 중심의 방대한 정보로 구성되어 가독성 저하
- 챔피언 변경, 아이템 업데이트 등 **관심 정보 탐색에 과도한 스크롤 필요**

---

## 3. 개선 방향 (What)

**“한눈에 핵심 정보를 파악할 수 있는 UX”** 를 중심으로 설계

- 사용자가 가장 자주 확인하는 정보는 **전면 배치**
- 긴 텍스트 콘텐츠는 **요약(Summary) + 빠른 이동 구조**로 개선
- 정보 탐색 흐름을 **직관적으로 재구성**

---

## 4. 구현 기능 (How)

### 📌 메인 페이지 개선
  - <details>
    <summary><b>개선 웹사이트 화면</b> (클릭해서 펼치기)</summary>
    <br/>
    <img width="1890" height="913" alt="image" src="https://github.com/user-attachments/assets/b3ed1961-8dee-4112-9872-142cc9b4480b" />
    <img width="1892" height="900" alt="image" src="https://github.com/user-attachments/assets/e01cbb7b-38d4-42f4-99d0-453bb874bdd8" />
  </details>

- **로그인 및 사용자 계정 정보(ID, 티어 등)**  
  → 화면 중앙 핵심 블록으로 배치
- **공지사항 / 패치 노트 게시판 재배치**  
  → 로그인 블록 양옆에 배치하여 시선 흐름 개선
- **LCK 하이라이트 영상 및 경기 일정 추가**  
  → 로그인 블록 하단에 배치하여 콘텐츠 확장


### 📌 패치 노트 페이지 개선

#### 🔹 왼쪽 SUMMARY 고정 메뉴 (Fixed Menu)
  - <details>
    <summary><b>개선 웹사이트 화면</b> (클릭해서 펼치기)</summary>
    <br/>
    <img width="1896" height="911" alt="image" src="https://github.com/user-attachments/assets/db65afa0-6f45-4197-b17e-1f01b1114dd2" />


  </details>
  - 사용자가 주로 관심을 가지는 정보 요약 제공  
    - 챔피언 상향/하향  
    - 아이템 업데이트  
    - 주요 시스템 변경  
  - 클릭 시 해당 상세 섹션으로 즉시 이동


#### 🔹 오른쪽 PATCH MENU 고정 메뉴 (Fixed Menu)
  - <details>
      <summary><b>개선 웹사이트 화면</b> (클릭해서 펼치기)</summary>
      <br/>
      <img width="1895" height="923" alt="image" src="https://github.com/user-attachments/assets/a293441d-e248-4e07-8d4c-35a50c125a74" />


    </details>
  - 패치 노트를 **헤드라인 기준으로 자동 목차화**
  - 원하는 항목으로 **빠른 섹션 이동 지원**

---

## 5. 기대 효과

- ✅ 정보 탐색 시간 단축
- ✅ 외부 전적 사이트 의존도 감소
- ✅ 신규/복귀 유저 모두에게 친화적인 UX 제공
- ✅ 패치 노트 가독성 및 사용성 대폭 향상

