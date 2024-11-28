## Crypto Tracker mk3

- Nomadcoders, React Master class 강의 2주 챌린지
- 암호화폐의 정보들을 모아서 보여주는 웹 페이지 개발하기
- **[강의 URL](https://nomadcoders.co/react-masterclass)**
- **📆 개발 기간: 2024.11.27 ~ 2024.11.29**
    - **프로젝트 마감: 2024.11.30 오전 6시**

---

#### 💻 사용 기술 목록
- 고정: `TypeScript`, `React`
- CSS : `styled-components`
- 상태 관리: `recoil`
- Routing: `react-router-dom version 6`
- API Data Fetch: `react-query`

---

### 📆 Day 1 작업 요약 (2024.11.27 수요일)

- **📑 "Project-Repository Connected"**
    - Crypto-Tracker mk3 Project File, Github 저장소 생성
    - Project Package, Github 저장소 연동

- **📑 "추가 Package 설치, 테마 변환 간략하게 구현"**
    - `styled-components`, `recoil`, `react-router-dom`, `react-query` 설치
    - 간단한 테마 변환 버튼 만들고 계속 테마를 변환하면서 <br/>
        각 테마 별로 적절한 색상 선정하였음.

- **📑 "Home 화면 구현 시작 (Coins data fetch)"**
    - Package 명 일부 변경, (`/modules`, `/routes → /Routes`)
    - Home 화면 구현 시작
        - Coin Paprika API로 암호화폐 1위부터 50위까지 가져옴
        - 그리고 가져온 정보를 웹 페이지에 출력 (id / name)
        - 테스트 용 Title 화면 추가 (전역으로 바꿀 예정)

### 📆 Day 2 작업 요약 (2024.11.28 목요일)

- **📑 "Home 화면 디자인 v1, 테마 변경 Toggle Button 추가**
    - **1. Home 화면 디자인 v1**
        - 코인 아이템에 코인 이름, 이미지 나오게 업데이트
        - 저번 회차에서는 코인에 마우스를 갖다댈 시 <br/>
            배경색을 살짝 밝게해서 하이라이트한 느낌이 나게 했지만 <br/>
        - 이번에는 코인 아이템의 배경색을 건드리지 않고 <br/>
            대신 `CSS scale` 속성의 값을 살짝 올리는 걸로 <br/>
            다른 형태로 하이라이트를 구현해봤다.

    - **2. 테마 변경 Toggle Button**
        - 저번에는 테마 변경 기능을 단순한 버튼으로만 구현했지만 <br/>
            이번에는 슬라이드 버튼 형식으로 구현해봤다.
        - 테마의 상태에 따라 `CSS transform` 속성을 통해 <br/>
            버튼이 실제로 움직이는 느낌의 Animation을 추가하였다.
