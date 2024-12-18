# 코난조

이 프로젝트는 **블록깨기 게임**을 **Pygame**을 사용해서 만들었습니다.

## 목차
- [다운로드](#다운로드-for-windows)
- [인게임 화면](#인게임-화면)
- [ChatGPT가 생성한 최초 버전](#최초-버전)
- [조작법](#조작법)
- [멤버](#멤버)

-----
# **벽돌깨기 게임 (Breakout Game)**

## **게임 개요**
`벽돌깨기`는 플레이어가 패들을 조작하여 공을 튕기고, 화면 상단의 벽돌을 제거하는 아케이드 게임입니다. 게임에는 다양한 색상의 벽돌, 특별한 아이템, 파괴 불가능한 벽돌 등이 포함되어 있으며, 모든 벽돌을 제거하거나 공을 잃지 않고 높은 점수를 얻는 것이 목표입니다.

---

## **게임 주요 기능**

### **1. 기본 메커니즘**
- **패들 조작**:
  - 화살표 키(`←`, `→`) 또는 `A`, `D` 키를 사용해 패들을 좌우로 이동합니다.
- **공 이동**:
  - 공은 벽, 패들, 벽돌 등과 충돌하며 반사됩니다.
- **벽돌 제거**:
  - 공이 벽돌과 충돌하면 벽돌이 제거되고, 점수가 증가합니다.

---

### **2. 특별 기능**

#### **아이템 시스템**
- **패들 크기 증가 아이템**:
  - 패들의 길이가 증가합니다.
- **공 개수 증가 아이템**:
  - 추가 공이 생성되어 여러 공을 동시에 다룰 수 있습니다.
- **파괴 불가능한 벽돌 생성 아이템**:
  - 제거할 수 없는 회색 벽돌이 새로 생성됩니다.

#### **난이도 조정**
- 패들의 어느 부분에 공이 튀기냐에 따라 공의 속도가 달라집니다.
- 추가로 패들이 늘어난 상태에서 끝쪽에 공이 맞으면 공이 훨씬 더 빨라집니다

---

### **3. 점수 및 시간**
- **점수 계산**:
  - 벽돌 제거 시 10점이 추가됩니다.
- **경과 시간**:
  - 게임 시작부터의 경과 시간이 상단에 표시됩니다.
  - 일시정지 동안은 타이머 시간이 흐르지 않습니다.
- **게임 횟수**:
  - 현재 진행 중인 게임 횟수가 표시됩니다.
  - 클리어 후 다시 게임 시작시 게임 횟수가 초기화 됩니다.

---

## **게임 화면**

### **1. 시작 화면**
- 시작 화면에서는 "Press Space To Start" 메시지가 표시됩니다.
- 플레이어는 스페이스바를 눌러 게임을 시작할 수 있습니다.

### **2. 플레이 화면**
- 벽돌, 패들, 공이 화면에 표시되며 게임이 진행됩니다.
- 화면 상단에는 점수, 경과 시간, 게임 횟수가 표시됩니다.

### **3. 게임 오버**
- 공이 모두 바닥에 떨어지면 "Game Over" 화면이 표시됩니다.
- 플레이어는 스페이스바를 눌러 게임을 재시작할 수 있습니다.

### **4. 게임 클리어**
- 모든 벽돌을 제거하면 "Game Clear" 화면이 표시됩니다.
- 최종 점수와 경과 시간이 화면에 표시되며, 스페이스바를 눌러 게임을 재시작할 수 있습니다.

### **4. 일시정지**
- 게임 도중 ESC 혹은 SPACE 키를 누르면 게임이 일시정지 됩니다.
- 일시정지 동안 타이머는 흐르지 않으며 다시 ESC 또는 SPACE 키를 눌러서 다시 이어서 할 수 있습니다.

---

## **게임 목표**
- 가능한 한 많은 점수를 얻고, 모든 벽돌을 제거하세요.
- 공이 화면 아래로 떨어지지 않도록 패들을 정확히 조작하세요.

---

## **개발 정보**

- **개발 도구**: Python, Pygame
- **주요 파일**:
  - `main.py`: 게임의 메인 코드
  - `background_image.jpeg`: 배경 이미지
  - `start_screen.jpg`: 시작 화면 이미지
  - `game_vict.jpg`: 게임 클리어 이미지
  - `Game_Over.jpg`: 게임 오버 이미지
- **기능 구현**:
  - 아이템 시스템
  - 스페셜 블록
  - 공 및 패들 충돌 처리

---

## 다운로드 (For Windows)
게임 다운로드

-----

## 인게임 화면

-----

## 최초 버전
ChatGPT가 생성한 최초 버전입니다. ( gif 이미지 ) 

![gpt_first](https://github.com/user-attachments/assets/06657891-16fa-496b-845b-564d36715004)

-----

## 조작법
| 키보드 입력 | 동작                              |
|-------------|-----------------------------------|
| `←`, `A`    | 패들을 왼쪽으로 이동              |
| `→`, `D`    | 패들을 오른쪽으로 이동            |
| `SPACE`     | 게임 시작 / 일시정지 / 재시작      |
| `ESC`       | 게임 일시정지 / 해제              |

-----

## 멤버

- [장진석](https://github.com/Jinseok2419342)
- [정현국](https://github.com/ehfl21)
- [고지호](https://github.com/jiho050718)
- [최은성](https://github.com/eunsg1)
- [김건우](https://github.com/urobo12)
- [김수한](https://github.com/suhan1029)
- [양경윤](https://github.com/kyungyunie)
