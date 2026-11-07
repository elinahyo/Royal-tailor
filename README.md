# Royal-tailor

동화 『벌거벗은 임금님』을 모티브로 한 모바일 싱글플레이 옷 만들기 게임, **왕실 수선소**입니다.

## 진행상황

**2026-11-07 기준:** A03에서 게임 경험을 재설계했습니다. 핵심 UI 48상태, 모션 트랙205개, 사운드 견본16종과 동기 영상을 Figma·저장소에 정리했습니다. 기존60맵·튜토리얼·게스트/로그인·MAX 정책은 유지합니다. Unity 구현과 실기기 검증은 다음 단계입니다.

- [최신 A03 진행상황 — 문제 분석·수정·검증 범위](docs/progress/2026-11-07-a03-game-feel.md)
- [Figma A03 게임 경험·모션·사운드](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=112-39)
- [48개 핵심 화면 목록](docs/progress/2026-11-07-a03-screen-index.md)
- [사운드와 함께 보는 납품·별 보상 영상](docs/art/feedback/a03/delivery-reward-review.mp4)
- [비주얼·사운드 구현 명세](docs/art/feedback/a03/game-feel-spec.md)

- [A02 구조 시안 기록 — 서비스 흐름·검증·남은 결정](docs/progress/2026-11-07-a02-ui.md)
- [111개 UI 상태와 개별 Figma 링크](docs/progress/2026-11-07-a02-ui-screen-index.md)
- [Figma A02 전체 UI 목차](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=78-58)
- [Figma 통합 시스템 플로우 v2.0](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=61-3)

- [진행상황 상세 보고서 — 완료 범위·검토할 제안값·다음 개발 순서](docs/progress/2026-11-06-planning-status.md)
- [A02 심플 로우폴리 콘셉트 — 오버쿡 정도의 단순함으로 수정 / 최신 검토용](docs/art/concepts/a02/README.md)
- [Figma 협업 시작점 — 상세 기획 8개와 화면·맵 시안](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=40-100)
- [Figma 전체 시스템 워크플로우](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=3-3)
- [Figma 60맵 레벨 기획](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=16-3)

## 게임 구성

독립 튜토리얼과 5개 에피소드로 구성합니다. 각 에피소드는 12개 정규 맵, 총 60개 맵이며 맵당 최대 5성으로 평가합니다. 튜토리얼은 정규 맵 수와 별 평가에서 제외합니다.

| 에피소드 | 이름 | 정규 맵 수 |
|---|---|---:|
| EP01 | 왕실의 부름 | 12 |
| EP02 | 변덕쟁이 임금님 | 12 |
| EP03 | 근위병 대소동 | 12 |
| EP04 | 왕궁 무도회 | 12 |
| EP05 | 이웃국가의 귀빈 | 12 |

아트 방향은 **A. 따뜻한 동화책 스타일 — 파스텔·둥근 로우폴리 3D**입니다. 모바일 싱글플레이, AppLovin MAX 선택형 보상 광고, 게스트/선택 로그인 흐름을 유지합니다. ‘보이지 않는 옷’ 엔딩 구성은 포함하지 않습니다.

## 다음 단계

1. 개발·디자인 담당자와 화면 방향, 기본 조작, 첫 구현 범위, 목표 기기를 검토합니다.
2. 독립 튜토리얼 TUT-01과 첫 정규 맵 EP01-01을 임시 모델로 구현합니다.
3. 저장·광고 보상·일시정지·앱 복귀와 실기기 조작감을 검증한 뒤 EP01-02~03으로 확대합니다.

연출·사운드는 [A03 구현 명세](docs/art/feedback/a03/game-feel-spec.md)를 기준으로 논의합니다. 재화·서비스 정책의 미확정값은 [A02 결정 항목](docs/progress/2026-11-07-a02-ui.md#개발-전에-결정할-항목)에 남겨 두었습니다. 이전 보고서는 당시의 기획 기록으로 보관합니다.
