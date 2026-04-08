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
  <br/>
  <img width="1899" height="904" alt="image" src="https://github.com/user-attachments/assets/c8827471-d3ac-4af5-8433-084ecd4735fa" />
  <img width="1902" height="907" alt="image" src="https://github.com/user-attachments/assets/a74a0b3a-0a0e-4873-844d-49bb7cc30545" />
  <img width="1901" height="907" alt="image" src="https://github.com/user-attachments/assets/668f1c0b-1008-4cc1-a0d6-9ee38c49cba2" />
  <img width="1896" height="904" alt="image" src="https://github.com/user-attachments/assets/50d78376-c3f4-4aeb-ba31-eaf8b8ea2351" />

</details>


- 유사한 성격의 콘텐츠가 중복 노출됨
- 사용자의 티어 정보 확인을 위해 **클라이언트에 접속하거나**
  OP.GG, FOW 등 **외부 사이트에 의존해야 하는 불편함** 존재

#### 📄 패치 노트 페이지
- <details>
  <summary><b>기존 웹사이트 화면</b> (클릭해서 펼치기)</summary>
  https://www.leagueoflegends.com/ko-kr/news/game-updates/patch-26-1-notes/
  <br/>
  <img width="1898" height="908" alt="image" src="https://github.com/user-attachments/assets/48ff70a3-7654-46bb-b75e-a4d3e80a0106" />
  <img width="1903" height="907" alt="image" src="https://github.com/user-attachments/assets/db5de53b-a9b6-49c9-b863-67fdf7d08358" />
  <img width="1897" height="906" alt="image" src="https://github.com/user-attachments/assets/557163e8-9484-41fc-8870-5ef435d0e684" />
  <img width="1898" height="905" alt="image" src="https://github.com/user-attachments/assets/7566bba5-f25b-44d8-aab6-7a3d1ea8dcd1" />


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
    <img width="1896" height="905" alt="image" src="https://github.com/user-attachments/assets/895e20b4-7438-483a-8196-ee87738c651f" />
    <img width="1898" height="905" alt="image" src="https://github.com/user-attachments/assets/1edaa1a4-c0f7-438e-93d9-23b0b1dd48cf" />
    <img width="1901" height="907" alt="image" src="https://github.com/user-attachments/assets/4d5cca0d-1df4-4a8e-8cfa-31432b4fd33c" />

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
    <img width="1896" height="901" alt="image" src="https://github.com/user-attachments/assets/1091a5d5-98c5-4580-9f90-0e81464f7d22" />

  </details>
  - 사용자가 주로 관심을 가지는 정보 요약 제공  
    - 챔피언 상향/하향  
    - 아이템 업데이트  
    - 주요 시스템 변경  
  - 클릭 시 해당 상세 섹션으로 **즉시 이동**


#### 🔹 오른쪽 PATCH MENU 고정 메뉴 (Fixed Menu)
  - <details>
      <summary><b>개선 웹사이트 화면</b> (클릭해서 펼치기)</summary>
      <br/>
      <img width="1895" height="904" alt="image" src="https://github.com/user-attachments/assets/5b1cb1a8-3b92-4d32-b245-2d021854d9d0" />

    </details>
  - 패치 노트를 **헤드라인 기준으로 자동 목차화**
  - 원하는 항목으로 **빠른 섹션 이동 지원**

---

## 5. 기대 효과

- ✅ 정보 탐색 시간 단축
- ✅ 외부 전적 사이트 의존도 감소
- ✅ 신규/복귀 유저 모두에게 친화적인 UX 제공
- ✅ 패치 노트 가독성 및 사용성 대폭 향상

