# A03 비주얼·사운드 검토 자료

[사운드 동기 영상](delivery-reward-review.mp4) · [통합 사운드만 듣기](delivery_reward_mix.wav) · [Figma 연출 명세](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=122-1036)

이 폴더의 사운드는 Royal-tailor를 위해 직접 합성한 **임시 견본**입니다. 최종 음악·Foley·기기 진동·믹싱 승인은 별도 작업입니다. 외부 음악이나 게임 음원을 복제하지 않았습니다.

## 영상 타이밍

| 영상 시점 | 사건 |
|---|---|
| 0.04초 | 납품 확인·밝은 칭찬음 |
| 0.40초 | 점수 도착을 받쳐 주는 짧은 톡 |
| 2.00초 | 결과 전환 |
| 2.25 / 2.49 / 2.73초 | 별1·2·3의 상승음 |
| 2.95초 | 코인 수령 |
| 3.60초 | 다음 주문 버튼 등장에 맞춘 상승음 |

영상 길이는5.2초이며, Figma에서10fps로 렌더한 연출 확인용입니다. 실제 게임의 목표60fps 동작을 검증한 영상은 아닙니다. Figma 디자인 타임라인 자체에는 오디오가 자동 연결되지 않습니다.

## 사운드 파일

| 파일 | 역할 | 길이 |
|---|---|---:|
| [ui_press.wav](ui_press.wav) | 활성 버튼의 작은 나무 톡 | 0.08초 |
| [cloth_pick.wav](cloth_pick.wav) | 원단을 드는 마찰음 | 0.18초 |
| [cut.wav](cut.wav) | 재단 가위 | 0.15초 |
| [sew_loop.wav](sew_loop.wav) | 작업 중 바느질 루프 | 0.30초 |
| [deliver.wav](deliver.wav) | 정확한 납품 확인 | 0.65초 |
| [star_1.wav](star_1.wav) | 첫 별 | 0.28초 |
| [star_2.wav](star_2.wav) | 두 번째 별 | 0.28초 |
| [star_3.wav](star_3.wav) | 세 번째 별 | 0.28초 |
| [coins.wav](coins.wav) | 코인 지급 | 0.50초 |
| [unlock.wav](unlock.wav) | 새 목표·맵 해금 | 0.62초 |
| [warning.wav](warning.wav) | 제한된 시간 경고 | 0.10초 |
| [fail.wav](fail.wav) | 차분한 실패·재도전 | 0.60초 |
| [countdown.wav](countdown.wav) | 3·2·1 준비 | 0.12초 |
| [go.wav](go.wav) | 시작 신호 | 0.30초 |
| [loading_swish.wav](loading_swish.wav) | 천 전환 | 0.30초 |
| [bgm_workshop_loop.wav](bgm_workshop_loop.wav) | 92BPM 플럭 BGM 견본 | 약5.22초 |

[기계 판독용 파일 정보](sound-manifest.json) · [이벤트별 발생·중단·중복 방지 규칙](game-feel-spec.md)

작업 루프는 작업 이탈·일시정지·광고·앱백그라운드에서 즉시 멈춥니다. 보상음은 지급 확정 뒤1회만 재생합니다. BGM·효과음·진동은 각각 끌 수 있고, 효과를 줄여도 목표와 보상 정보는 동일하게 표시합니다.
