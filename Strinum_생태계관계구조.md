# Strinum 생태계 관계 구조

## 1. 계층 구조

SUL
  ↓
Strinum
  ↓
FrameSet
  ↓
Runtime
  ↑
S++MODE (메타 통제 계층)

---

## 2. 종속 관계

SUL은 독립적이다.

Strinum은 SUL에 의존한다.

FrameSet은 Strinum 출력에 의존한다.

Runtime은 FrameSet에 의존한다.

S++MODE는 전체를 통제한다.

---

## 3. 공개 / 비공개 경계

공개:
- 철학
- 명세
- FrameSet Core 인터페이스

비공개:
- 결정적 실행 엔진
- 메모리 지속 시스템
- 고급 AI 실행 계층
