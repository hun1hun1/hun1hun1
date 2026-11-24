# hun1hun1

게임 클라이언트 프로그래머를 준비하고 있습니다.
주로 C++을 사용하며, Unity와 Unreal Engine으로 게임을 개발합니다.

## 대표 프로젝트

### [D&N](https://github.com/hun1hun1/Unity_ProjectDN)

**Unity · C#** · 꿈과 악몽, 두 덱을 사용하는 2D 덱빌딩 로그라이크 프로토타입

- 카드 효과와 적 행동을 ScriptableObject로 구성했습니다.
- 전투·상점·휴식 등으로 이어지는 1층 13노드의 진행을 구현했습니다.
- 체크포인트로 런 진행을 복원하고, 상점 구매 저장에 실패하면 골드·덱·재고를 거래 전 상태로 되돌리도록 구현했습니다.

[체크포인트 및 이어서 하기 설계](https://github.com/hun1hun1/Unity_ProjectDN/blob/main/docs/RunCheckpoints.md)

### [MoreApple](https://github.com/hun1hun1/MoreApple)

**C++ · Direct2D** · 60초 안에 떨어지는 과일을 바구니로 받아 목표선까지 쌓는 2D 아케이드 게임

- 첫 과일은 원형 과일과 사각형 바구니의 충돌로 받습니다. 이후에는 맨 위 과일과 새로 떨어지는 과일 사이의 원형 충돌을 판정해 과일을 쌓습니다.
- D2B(Day2Build) 팀으로 1.44MB 공모전에 참가해 콘텐츠 개발과 테스트를 담당했습니다. MoreApple은 팀 작품인 1.44MB Multi-Arcade에 수록되었습니다.

[1.44MB Multi-Arcade 팀 저장소](https://github.com/sin49/1.44_2)

## 학습 기록

- [TIL](https://github.com/hun1hun1/TIL) — 알고리즘 학습 노트
- [C++ Coding Test](https://github.com/hun1hun1/CPP_CODING_TEST) — C++ 문제 풀이 기록

---

# English

I'm preparing for a career in game client programming.
I primarily use C++ and develop games with Unity and Unreal Engine.

## Featured Project

### [D&N](https://github.com/hun1hun1/Unity_ProjectDN)

**Unity · C#** · A 2D deckbuilding roguelike prototype built around two decks, Dream and Nightmare.

- Used ScriptableObjects to define card effects and enemy behaviors.
- Implemented a 13-node first floor with battles, shops, and rest stops.
- Implemented checkpoint-based run recovery. If saving a shop purchase fails, the game restores the gold balance, deck, and shop inventory to their pre-purchase state.

[Checkpoint and resume system](https://github.com/hun1hun1/Unity_ProjectDN/blob/main/docs/RunCheckpoints.md)

### [MoreApple](https://github.com/hun1hun1/MoreApple)

**C++ · Direct2D** · A 2D arcade game where players have 60 seconds to catch falling fruit and stack it up to the goal line.

- The first catch uses a circle-to-rectangle collision check between the fruit and the basket. Each subsequent catch uses a circle-to-circle check against the fruit at the top of the stack.
- I worked on game content and testing with Team D2B (Day2Build) for the 1.44MB competition. MoreApple was included in our team's 1.44MB Multi-Arcade collection.

[1.44MB Multi-Arcade team repository](https://github.com/sin49/1.44_2)

## Study Notes

- [TIL](https://github.com/hun1hun1/TIL) — Algorithm study notes
- [C++ Coding Test](https://github.com/hun1hun1/CPP_CODING_TEST) — Coding problem solutions in C++

## My Github Stats
![GitHub Stats](https://github-readme-stats-fast.vercel.app/api/top-langs/?username=hun1hun1&layout=compact&theme=dark)\
![GitHub Stats](https://github-readme-stats-fast.vercel.app/api?username=hun1hun1&count_private=true&show_icons=true&theme=dark&include_all_commits=true)
