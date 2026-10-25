# Completing an exercise (meditation) from Meditate

- Mobbin 상세 페이지: https://mobbin.com/flows/2f47389f-316e-4118-8cca-2ad0323be980?tab=screens
- 앱·기기: stoic. iOS, 393×852
- 화면 수: 상세 페이지 6장 / 저장 이미지 6장 / 아래 설명 6개
- 검증 상태: **verified** — 목록 제목·상세 제목·URL과 화면별 이미지 수·순서·상태 변화를 대조했다.

```mermaid
flowchart TD
  S1["meditate.의 Unguided 카드에 Begin이 보인다."]
  S1 -->|Begin을 누른다.| S2
  S2["Unguided 시트에 10분 눈금과 Begin Meditation이 보인다."]
  S2 -->|길이를 1분으로 조정한다.| S3
  S3["눈금의 선택값이 1분으로 바뀌었다."]
  S3 -->|Begin Meditation을 누른다.| S4
  S4["명상 전체 화면에 추상 원형 선과 00:59 left가 나타난다."]
  S4 -->|남은 시간 동안 명상을 진행한다.| S5
  S5["01:02 total time과 Finish, Log +00:02가 보인다."]
  S5 -->|Finish를 누른다.| S6
  S6["Good job! You've Completed Meditation과 01:00, 피드백 선택지가 나타난다."]
```

## 화면별 기록

1. ![화면 1](screenshots/screen-01.webp) `meditate.`의 Unguided 카드에 `Begin`이 보인다. `Begin`을 누른다. 다음 화면에서는 Unguided 시트에 10분 눈금과 `Begin Meditation`이 보인다.
2. ![화면 2](screenshots/screen-02.webp) Unguided 시트에 10분 눈금과 `Begin Meditation`이 보인다. 길이를 1분으로 조정한다. 다음 화면에서는 눈금의 선택값이 1분으로 바뀌었다.
3. ![화면 3](screenshots/screen-03.webp) 눈금의 선택값이 1분으로 바뀌었다. `Begin Meditation`을 누른다. 다음 화면에서는 명상 전체 화면에 추상 원형 선과 `00:59 left`가 나타난다.
4. ![화면 4](screenshots/screen-04.webp) 명상 전체 화면에 추상 원형 선과 `00:59 left`가 나타난다. 남은 시간 동안 명상을 진행한다. 다음 화면에서는 `01:02 total time`과 `Finish`, `Log +00:02`가 보인다.
5. ![화면 5](screenshots/screen-05.webp) `01:02 total time`과 `Finish`, `Log +00:02`가 보인다. `Finish`를 누른다. 다음 화면에서는 `Good job! You've Completed Meditation`과 01:00, 피드백 선택지가 나타난다.
6. ![화면 6](screenshots/screen-06.webp) `Good job! You've Completed Meditation`과 01:00, 피드백 선택지가 나타난다.

## BMad handoff notes

- **관찰된 진입 상태:** meditate 섹션의 Unguided 명상.
- **주요 행동:** 길이를 1분으로 바꾸고 명상을 시작한 뒤 Finish로 끝낸다.
- **기대 결과:** 완료 화면에 01:00이 기록된다. 피드백 전송 결과는 확인 불가.
- **되돌릴 수 있거나 파괴적인 동작:** 실행 중 종료와 마지막 화면의 Add note가 보인다. 기록 삭제 경로는 확인 불가.
