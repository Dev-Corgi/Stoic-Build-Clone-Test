# Completing a lesson from Collection detail

- Mobbin 상세 페이지: https://mobbin.com/flows/92380915-d1d3-4c2b-b2da-f6f7a6e2c84b?tab=screens
- 앱·기기: stoic. iOS, 393×852
- 화면 수: 상세 페이지 6장 / 저장 이미지 6장 / 아래 설명 6개
- 검증 상태: **verified** — 목록·상세 제목·URL과 이미지 6장의 순서를 대조했다. 피드백 선택지와 건너뛰기는 같은 `Up next!`로 진행하고, 이후 `Finish for now`를 눌렀다는 사용자 확인을 받았다. 특정 피드백 값은 확인 불가.

```mermaid
flowchart TD
  S1["On Good Life"]
  S1 -->|Begin을 누른다.| S2
  S2["On Good Mornings"]
  S2 -->|진행 화살표로 성찰 질문으로 이동한다.| S3
  S3["Imagine a perfect day.."]
  S3 -->|답변을 완료하고 다음으로 진행한다.| S4
  S4["Good job! 화면에 첫 수업 완료, 4 words와 Did you enjoy this journal? 피드백 질문이 보인다."]
  S4 -->|피드백 항목 하나 또는 건너뛰기를 선택해 Up next!로 이동| S5
  S5["Up next!에 다음 수업 안내와 Go to the next part, Finish for now가 보인다."]
  S5 -->|Finish for now를 누른다.| S6
  S6["컬렉션 상세로 돌아와 On Good Mornings가 Read와 체크로 표시된다."]
```

## 화면별 기록

1. ![화면 1](screenshots/screen-01.webp) `On Good Life.` 컬렉션의 첫 카드 `On Good Mornings`에 `Begin`이 보인다. `Begin`을 누른다. 다음 화면에서는 `On Good Mornings.` 수업의 도입 설명과 오른쪽 진행 화살표가 보인다.
2. ![화면 2](screenshots/screen-02.webp) `On Good Mornings.` 수업의 도입 설명과 오른쪽 진행 화살표가 보인다. 진행 화살표로 성찰 질문으로 이동한다. 다음 화면에서는 `Imagine a perfect day...` 질문에 아침·오후·저녁 일정을 적은 답변이 있고 오른쪽 진행 화살표가 보인다.
3. ![화면 3](screenshots/screen-03.webp) `Imagine a perfect day...` 질문에 아침·오후·저녁 일정을 적은 답변이 있고 오른쪽 진행 화살표가 보인다. 답변을 완료하고 다음으로 진행한다. 다음 화면에서는 `Good job!` 화면에 첫 수업 완료, 4 words와 `Did you enjoy this journal?` 피드백 질문이 보인다.
4. ![화면 4](screenshots/screen-04.webp) `Good job!` 화면에 첫 수업 완료, 4 words와 `Did you enjoy this journal?` 피드백 질문이 보인다. 피드백 항목 하나를 선택하거나 건너뛰면 모두 `Up next!`로 이동한다(사용자 확인). 캡처에서 선택한 특정 값은 확인 불가. 다음 화면에서는 `Up next!`에 다음 수업 안내와 `Go to the next part`, `Finish for now`가 보인다.
5. ![화면 5](screenshots/screen-05.webp) `Up next!`에 다음 수업 안내와 `Go to the next part`, `Finish for now`가 보인다. `Finish for now`를 누른다(사용자 확인). 다음 화면에서는 컬렉션 상세로 돌아와 `On Good Mornings`가 `Read`와 체크로 표시된다.
6. ![화면 6](screenshots/screen-06.webp) 컬렉션 상세로 돌아와 `On Good Mornings`가 `Read`와 체크로 표시된다.

## BMad handoff notes

- **관찰된 진입 상태:** On Good Life 컬렉션의 첫 수업 카드.
- **주요 행동:** 첫 수업을 시작하고 완벽한 하루 질문에 답한 뒤 피드백 단계를 지나 `Finish for now`를 누른다.
- **기대 결과:** 수업 완료와 다음 수업 안내가 나오며 컬렉션 카드에 완료 체크가 붙는다.
- **되돌릴 수 있거나 파괴적인 동작:** 완료된 수업은 Read로 재열람 가능하다. 답변 수정·삭제 경로는 확인 불가.
