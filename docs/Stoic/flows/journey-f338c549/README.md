# Journey

- Mobbin 상세 페이지: https://mobbin.com/flows/f338c549-c18a-45db-81f1-12819c1eadfa?tab=screens
- 앱·기기: stoic. iOS, 393×852
- 화면 수: 상세 페이지 6장 / 저장 이미지 6장 / 아래 설명 6개
- 검증 상태: **verified** — 목록·상세 제목·URL과 이미지 6장의 순서를 대조했다. 빈 Journey와 14개 기록이 있는 Journey는 사용자가 수일에 걸쳐 앱을 사용한 전후 상태라는 확인을 받았다. 중간 기록 생성 화면은 이 상세 페이지에 없다.

```mermaid
flowchart TD
  S1["Today 탭의 아침 준비 Begin 카드와 성찰 카드가 보인다."]
  S1 -->|하단 Journey 탭을 누른다.| S2
  S2["Journey의 빈 Insights 카드와 Write Your First Journal이 보인다."]
  S2 -->|수일간 저널·성찰·운동 기록을 쌓은 뒤 Journey 재방문| S3
  S3["July Insights에 Entries 14, Avg"]
  S3 -->|아래로 스크롤한다.| S4
  S4["오늘 Morning Reflection 본문과 사진, Kōans walk 항목이 보인다."]
  S4 -->|아래로 더 스크롤한다.| S5
  S5["Mood Check-In과 Breathing Alternate 기록 아래 어제 Evening Reflection이 보인다."]
  S5 -->|아래로 더 스크롤한다.| S6
  S6["어제 Evening Reflection의 감정 태그와 사진 격자가 보인다."]
```

## 화면별 기록

1. ![화면 1](screenshots/screen-01.webp) Today 탭의 아침 준비 Begin 카드와 성찰 카드가 보인다. 하단 `Journey` 탭을 누른다. 다음 화면에서는 Journey의 빈 `Insights` 카드와 `Write Your First Journal`이 보인다.
2. ![화면 2](screenshots/screen-02.webp) Journey의 빈 `Insights` 카드와 `Write Your First Journal`이 보인다. 수일간 앱을 사용하며 기록을 쌓은 뒤 Journey에 다시 방문한 상태다(사용자 확인). 데이터 생성 과정은 이 상세 페이지에 없다. 다음 화면에서는 `July Insights`에 Entries 14, Avg. Sleep Okay, Avg. Stress Some과 오늘의 저널·성찰이 보인다.
3. ![화면 3](screenshots/screen-03.webp) `July Insights`에 Entries 14, Avg. Sleep Okay, Avg. Stress Some과 오늘의 저널·성찰이 보인다. 아래로 스크롤한다. 다음 화면에서는 오늘 Morning Reflection 본문과 사진, Kōans walk 항목이 보인다.
4. ![화면 4](screenshots/screen-04.webp) 오늘 Morning Reflection 본문과 사진, Kōans walk 항목이 보인다. 아래로 더 스크롤한다. 다음 화면에서는 Mood Check-In과 Breathing Alternate 기록 아래 어제 Evening Reflection이 보인다.
5. ![화면 5](screenshots/screen-05.webp) Mood Check-In과 Breathing Alternate 기록 아래 어제 Evening Reflection이 보인다. 아래로 더 스크롤한다. 다음 화면에서는 어제 Evening Reflection의 감정 태그와 사진 격자가 보인다.
6. ![화면 6](screenshots/screen-06.webp) 어제 Evening Reflection의 감정 태그와 사진 격자가 보인다.

## BMad handoff notes

- **관찰된 진입 상태:** Today 탭에서 Journey로 진입한다.
- **주요 행동:** Journey 탭을 열고, 수일간 앱 사용으로 기록이 누적된 뒤 날짜별 기록 목록을 아래로 탐색한다.
- **기대 결과:** Insights와 날짜별 저널·성찰·기분·운동 기록이 보인다.
- **되돌릴 수 있거나 파괴적인 동작:** 탭과 스크롤은 되돌릴 수 있다. 기록 삭제는 관찰되지 않는다.
