with open("turtle_runaway.md", "w", encoding="utf-8") as f:
    f.write("""# Turtle Runaway 게임 설명

## 1. 개요
이 프로그램은 Python turtle 모듈을 활용한 간단한 추격전 게임입니다.
플레이어(Chaser)는 키보드로 조작하며, Runner는 AI로 도망가는 알고리즘을 실행합니다.

목표는 제한 시간 내에 Runner가 잡히지 않으면 Runner 승리, 잡히면 Chaser 승리입니다.

---

## 2. 구현 내용
- 타이머: 남은 시간 표시
- Runner AI: 추격자를 회피하는 지능형 행동
- 점수 시스템: 잡히면 Chaser 승리, 제한 시간 버티면 Runner 승리
- 추가: 창 제목/배경색 설정, wrap-around 기능

---

## 3. 실행 방법
1. turtle_runaway.py 실행
2. ↑ ↓ ← → 키로 Chaser 조작
3. 제한 시간(20초) 동안 Runner를 잡으면 Chaser 승리, 아니면 Runner 승리
""")
