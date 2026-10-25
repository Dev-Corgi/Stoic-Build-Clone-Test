# Collection detail from Collections

- Mobbin 상세 페이지: https://mobbin.com/flows/dc9e8970-ab4c-4c12-8d72-b0dc689ff805?tab=screens
- 앱·기기: stoic. iOS, 393×852
- 화면 수: 상세 페이지 4장 / 저장 이미지 4장 / 아래 설명 4개
- 검증 상태: **blocked** — 첫 수업의 시작 전·완료 후 캡처 사이 수행 화면이 없어 완료 행동을 확인할 수 없다.

```mermaid
flowchart TD
  S1["collections"]
  S1 -->|On Good Life를 연다.| S2
  S2["On Good Life"]
  S2 -->|첫 수업을 완료한다| S3
  S3["첫 수업 카드가 Read와 완료 체크로 바뀐다."]
  S3 -->|카드 열을 가로로 이동한다.| S4
  S4["두 번째 수업 On Good Focus.에 Begin이 표시된다."]
```

## 화면별 기록

1. ![화면 1](screenshots/screen-01.webp) `collections.` 그리드에 `On Good Life 0/4`, `On ADHD 0/5`, `Embrace the New Year 0/4`가 보인다. `On Good Life`를 연다. 다음 화면에서는 `On Good Life.` 상세에 컬렉션 설명과 첫 수업 `On Good Mornings`의 `Begin`이 보인다.
2. ![화면 2](screenshots/screen-02.webp) `On Good Life.` 상세에 컬렉션 설명과 첫 수업 `On Good Mornings`의 `Begin`이 보인다. 첫 수업을 완료한다. 이 플로우에는 중간 수업 화면이 없다. 다음 화면에서는 첫 수업 카드가 `Read`와 완료 체크로 바뀐다.
3. ![화면 3](screenshots/screen-03.webp) 첫 수업 카드가 `Read`와 완료 체크로 바뀐다. 카드 열을 가로로 이동한다. 다음 화면에서는 두 번째 수업 `On Good Focus.`에 `Begin`이 표시된다.
4. ![화면 4](screenshots/screen-04.webp) 두 번째 수업 `On Good Focus.`에 `Begin`이 표시된다.

## BMad handoff notes

- **관찰된 진입 상태:** Collections의 미완료 컬렉션 그리드.
- **주요 행동:** On Good Life 컬렉션을 열어 첫 수업을 완료한 뒤 다음 카드를 탐색한다.
- **기대 결과:** 첫 카드가 완료 표시로 바뀌고 다음 수업에 Begin이 보인다.
- **되돌릴 수 있거나 파괴적인 동작:** 완료된 수업을 Read로 다시 열 수 있다. 완료 취소·삭제 경로는 확인 불가.
