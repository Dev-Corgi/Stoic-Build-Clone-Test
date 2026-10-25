# Subscribing to premium from Onboarding

- Mobbin 상세 페이지: https://mobbin.com/flows/3b7a09b5-ff45-4211-934c-9d92c60be08a?tab=screens
- 앱·기기: stoic. iOS, 393×852
- 화면 수: 상세 페이지 13장 / 저장 이미지 13장 / 아래 설명 13개
- 검증 상태: **verified** — 목록 카드 제목과 상세 제목 `Subscribing to premium on stoic.` 및 URL을 대조했고 이미지 1~13의 순서와 상태 변화를 확인했다.

```mermaid
flowchart TD
  S1[Premium + AI 혜택과 무료 체험 버튼] -->|혜택 영역 스크롤| S2[분석·알림·저널 혜택 목록]
  S2 -->|아래로 스크롤| S3[평점과 후기]
  S3 -->|후기 카드 이동| S4[다른 사용자 후기]
  S4 -->|아래로 스크롤| S5[다른 요금제 보기]
  S5 -->|Show Other Premium Plans| S6[연간·월간 / AI 포함 요금제 선택]
  S6 -->|Yearly 선택| S7[연간 일반 Premium 선택]
  S7 -->|Try 7 days free| S8[처리 중 표시]
  S8 -->|처리 완료| S9[구매 성공 대화상자]
  S9 -->|OK| S10[Premium 축하와 기능 설정]
  S10 -->|아래로 스크롤| S11[AI 설정과 구독 관리]
  S11 -->|아래로 스크롤| S12[Yearly 요금제 확인]
  S12 -->|Continue| S13[Today 홈]
```

## 화면별 기록

1. ![화면 1](screenshots/screen-01.webp) Premium + AI 제안에 AI 혜택과 연간 $99.99, `Try 3 days free`가 보인다. 혜택 영역을 아래로 내리면 다음 화면에서 기능 목록의 하단이 나타난다.
2. ![화면 2](screenshots/screen-02.webp) `Reflective Analysis`, `Smart Notifications`, `Morning & Evening Reflections`, `Daily Prompts & Guided Journals`, `See features included in your plan`이 보인다. 아래로 더 스크롤하면 별점과 사용자 후기가 표시된다.
3. ![화면 3](screenshots/screen-03.webp) 5개 별과 `89k+ 5-star reviews`, 사용자 후기 카드가 표시된다. 후기 카드를 이동하면 다음 화면에서 다른 후기가 보인다.
4. ![화면 4](screenshots/screen-04.webp) 다른 사용자 후기 아래에도 연간 + AI 가격과 무료 체험 버튼이 고정되어 있다. 아래로 스크롤하면 `Show Other Premium Plans`가 나온다.
5. ![화면 5](screenshots/screen-05.webp) 화면 하단에 `Show Other Premium Plans`, `Restore Purchase`, `Terms & Conditions`가 보인다. `Show Other Premium Plans`를 누르면 네 가지 요금제 선택 화면으로 이동한다.
6. ![화면 6](screenshots/screen-06.webp) 일반 Premium과 Premium AI 각각의 연간·월간 가격 네 칸이 나타나며 `Yearly + AI`가 선택되어 있다. 일반 `Yearly`를 선택하면 다음 화면에서 그 칸이 검게 강조되고 하단 가격이 바뀐다.
7. ![화면 7](screenshots/screen-07.webp) 일반 Premium `Yearly $39.99/year`가 검게 선택되어 있고 하단에 `Try 7 days free`가 표시된다. 이 버튼을 누른 뒤 다음 화면은 처리 중 상태다.
8. ![화면 8](screenshots/screen-08.webp) 요금제 화면이 흐려지고 `One Second` 로딩 표시가 겹쳐 있다. 처리 완료 후 다음 화면에서 구매 성공 대화상자가 나타난다.
9. ![화면 9](screenshots/screen-09.webp) iOS 대화상자에 `You're all set`과 `Your purchase was successful.`이 명시되어 있다. `OK`를 누르면 Premium 기능 안내로 이동한다.
10. ![화면 10](screenshots/screen-10.webp) `You have stoic premium!` 아래 iCloud 동기화·Face ID 보호 토글과 AI 플랜 업그레이드 항목이 보인다. 아래로 스크롤하면 AI 옵션과 구독 관리 항목이 더 표시된다.
11. ![화면 11](screenshots/screen-11.webp) `Upgrade to AI plan`, 개인화 정보, AI 성찰·알림 토글과 `Your plan: Yearly`, `Manage Subscriptions`가 보인다. 아래로 내리면 구독 정보와 감사 문구가 나타난다.
12. ![화면 12](screenshots/screen-12.webp) `Your plan: Yearly`, `Manage Subscriptions`, `View All Premium Plans`와 지원 감사 문구가 보인다. `Continue`로 진행하면 Today 홈으로 이동한다.
13. ![화면 13](screenshots/screen-13.webp) Today 탭에 `good evening.`, `Morning Preparation`의 `Begin`, 성찰 카드의 `Reflect`가 보인다. 이후 실제 사용이나 구독 관리 결과는 화면에서 확인 불가.

## BMad handoff notes

- **관찰된 진입 상태:** 온보딩 직후 Premium + AI 제안 화면에서 시작한다.
- **주요 행동:** 혜택과 후기를 살펴본 뒤 다른 요금제를 열고 일반 Premium 연간 플랜을 선택해 `Try 7 days free`로 진행한다.
- **기대 결과:** 구매 성공 대화상자, Premium 기능 안내, `Your plan: Yearly` 확인 후 Today 홈이 표시된다.
- **되돌릴 수 있거나 파괴적인 동작:** `Manage Subscriptions`와 `Restore Purchase` 진입점은 보인다. 무료 체험의 실제 청구·취소 시점과 취소 결과는 화면에서 확인 불가. 삭제 동작은 없다.
