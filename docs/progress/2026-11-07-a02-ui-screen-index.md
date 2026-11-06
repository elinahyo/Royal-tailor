# A02 UI 화면 목록

기준일: 2026-11-07 (한국 시간). 111개 UI 상태와 검증 프레임 3개입니다. 같은 화면의 성공·실패·보상·복구 상태를 별도 프레임으로 나누었습니다.

[전체 화면 목차](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=78-58) · [화면별 바로가기 패널](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=97-1970)

| 화면 ID | 화면 | Figma | 구현·검토 메모 |
|---|---|---|---|
| boot | 앱 실행 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=83-32) | BOOT → 로컬 데이터 확인 → 시작 화면 |
| title | 처음 시작 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=83-43) | 게스트 우선 · 로그인은 선택 확장 · 등록 강제 없음 |
| home | 공방 홈 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=83-60) | 복귀 유저 예시 · EP01-08까지 해금 · 보유 코인 320 |
| privacy | 개인정보·광고 설정 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=83-99) | 앱 안내 화면 · 실제 CMP / ATT 시스템 UI는 제공 SDK에서 표시 |
| privacyProvider | 광고 동의 제공 화면 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=83-131) | 외부 UI 표시 자리: 국가·OS·연령에 따라 CMP/ATT 화면을 호출. 법률 문안 확정 아님 |
| tutIntro | 독립 튜토리얼 안내 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=83-157) | 정규 60맵과 별도 · 별 평가·하트 소모·광고 없음 |
| tutMove | 이동 익히기 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=83-193) | 튜토리얼 1/5 · 시간 제한 없음 · 마지막 완료 단계부터 복구 |
| tutPick | 원단 집기 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=83-226) | 튜토리얼 2/5 · 시간 제한 없음 · 마지막 완료 단계부터 복구 |
| tutCut | 재단 익히기 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=83-259) | 튜토리얼 3/5 · 시간 제한 없음 · 마지막 완료 단계부터 복구 |
| tutSew | 재봉 익히기 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=83-292) | 튜토리얼 4/5 · 시간 제한 없음 · 마지막 완료 단계부터 복구 |
| tutDeliver | 첫 옷 납품 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=83-325) | 튜토리얼 5/5 · 시간 제한 없음 · 마지막 완료 단계부터 복구 |
| tutDone | 튜토리얼 완료 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=83-358) | 정규 별·코인 없음 · EP01-01 진입 |
| tutSkip | 튜토리얼 건너뛰기 확인 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=83-374) | 스킵 후 EP01-01 · 설정과 홈에서 다시 배우기 |
| episodes | 에피소드 선택 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=84-71) | 5 EP × 12맵 · EP01 진행 중 / EP02~05 잠금 예시 |
| map1 | EP01 · 12개 맵 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=84-135) | 12개 고유 맵 카드 · 완료/도전 가능/잠금 · 플레이 연결 대표 01-01, 01-08 |
| map2 | EP02 · 12개 맵 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=84-376) | 12개 고유 맵 카드 · 완료/도전 가능/잠금 · 플레이 연결 대표 01-01, 01-08 |
| map3 | EP03 · 12개 맵 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=84-591) | 12개 고유 맵 카드 · 완료/도전 가능/잠금 · 플레이 연결 대표 01-01, 01-08 |
| map4 | EP04 · 12개 맵 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=84-806) | 12개 고유 맵 카드 · 완료/도전 가능/잠금 · 플레이 연결 대표 01-01, 01-08 |
| map5 | EP05 · 12개 맵 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=84-1021) | 12개 고유 맵 카드 · 완료/도전 가능/잠금 · 플레이 연결 대표 01-01, 01-08 |
| mapLocked | 맵 잠금 안내 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=84-1236) | 잠금 조건 표시 · 시작 비활성 · 맵 목록으로 복귀 |
| prep | 스테이지 준비 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=84-1263) | STAGE_PREP · 하트 확인만 / 시작 시 차감 없음 · EP01-08 대표 예시 |
| boosters | 준비 아이템 선택 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=84-1299) | 보유 → 코인/선택 광고 · 효과와 지속 시간 표시 · 가격은 미확정 예시 |
| buyBooster | 부스터 획득 방법 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=84-1339) | 코인 가격 80은 UI 예시/미확정 · 광고 지급 시 재고 +1 후 선택 |
| coinShort | 코인 부족 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=84-1371) | 구매 취소 시 재화 미차감 · 광고 또는 무아이템 진행 |
| boosterReady | 보유 부스터 선택 완료 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=84-1400) | 재고 1개 → 시작 시 1개 소진 · 구매/광고 별도 |
| boosterOwned | 부스터 획득 완료 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=84-1428) | 구매 예시: 320−80=240 / 광고 경로는 코인 변화 없이 재고만 +1 |
| firstPrep | 첫 왕실 주문 준비 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=84-1454) | TUT 이후 EP01-01 · 2분 / 파랑 셔츠 1벌 · 하트 면제 |
| firstRun | 첫 맵 플레이 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=84-1485) | EP01-01 대표 한 판 · 튜토리얼과 분리 · 하트 면제 |
| firstSew | 첫 맵 재봉·납품 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=84-1518) | 첫 맵 핵심 공정 연결 시안 · 실제 이동/타이머는 Unity 구현 |
| firstWin | 첫 맵 클리어 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=84-1551) | 첫 1성 기본 100 + 최초 별 20 = 120 예시 · 광고는 선택 |
| playIdle | 플레이 · 대상 없음 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=85-987) | RUNNING · 왼손 이동/오른손 행동 · 대상 없으면 비활성 |
| craftReady | 플레이 · 재단 가능 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=85-1022) | 정확한 원단 확인 → 재단 버튼 · 수작업 이탈 시 중단 |
| crafting | 플레이 · 재단 중 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=85-1056) | 수작업 진행 · 이동하면 중단/진행 보존 |
| sewing | 플레이 · 자동 재봉 완료 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=85-1089) | 자동 재봉은 이동해도 계속 · 완료 아이콘과 회수 버튼 |
| readyDeliver | 플레이 · 완성품 납품 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=85-1122) | 완성품 소지 · 목표 납품대로 이동 |
| delivery | 플레이 · 정확한 납품 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=85-1155) | 정확한 납품 점수 +150 예시 · 최종 점수 570 → 3성 |
| wrongDelivery | 플레이 · 납품 오류 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=85-1188) | 구체적 오류 사유 · 점수 −30 예시 · 재제작 안내 |
| warning10 | 플레이 · 남은 10초 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=85-1223) | 30초/10초 경고 · 게임 진행 유지 · 자동 광고 없음 |
| pause | 일시정지 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=85-1257) | 라운드·주문·공정 타이머 동시 정지 · 복귀 시 입력 초기화 |
| restartConfirm | 재시작 확인 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=85-1289) | 이번 판 초기화 확인 · 자발적 재시작의 하트 정산 정책은 확정 필요 |
| exitConfirm | 맵 선택으로 나가기 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=85-1319) | 진행 중인 판 종료 확인 · 자발적 종료 하트 정산 정책 확정 필요 |
| timeout | 시간 종료 · 광고 이어하기 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=85-1348) | TIMEOUT_PENDING · 모래시계 0개 · 실패 확정 전 하트 차감 없음 |
| resume40 | 40초 이어하기 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=85-1382) | 보상 확인 후 RUNNING 복귀 · 두 번째 연장 없음 |
| playBoosted | 플레이 · 장화 활성 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=85-1416) | 보유 아이템 1개 소진 · 30초 효과 게이지 |
| timeoutItem | 시간 종료 · 보유 아이템 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=85-1450) | 모래시계 보유 1개 → 1개 사용 / 광고 없이 +40초 |
| result1 | 결과 · 1성 클리어 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1068) | v2.0 예시: 기본 100 + 새 별 1×20 = 120 / 광고는 기본 코인의 50%만 |
| result3 | 결과 · 3성 클리어 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1102) | v2.0 예시: 기본 100 + 새 별 3×20 = 160 / 광고는 기본 코인의 50%만 |
| result5 | 결과 · 5성 장인 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1136) | v2.0 예시: 기본 100 + 새 별 5×20 = 200 / 광고는 기본 코인의 50%만 |
| resultRepeat | 결과 · 재도전 최고 기록 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1170) | v2.0 예시: 기본 25 + 새 별 2×20 = 65 / 광고는 기본 코인의 50%만 |
| failed | 결과 · 실패 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1204) | 0성 / 0코인 · 실패 확정 때만 하트 4→3 · 최고 기록 유지 |
| resultBonus | 결과 · 광고 보너스 수령 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1233) | 3성 첫 클리어 160 + 광고 기본100×50%=50 → 총210 · 추가지급1회 |
| episodeDone | 에피소드 완료 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1265) | EP01-12 첫 1성 이상 완료 · EP02 해금 · 엔딩 아님 |
| hearts0 | 하트 0개 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1282) | 30분마다 +1 / 최대5 · 0→5는150분 · 무료 연습 접근 |
| heartRecovered | 하트 회복 완료 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1314) | 하트0→1 · 최대5 · 기존 회복 타이머 유지 |
| failedLast | 결과 · 마지막 하트 소모 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1342) | 실패 확정 하트1→0 · 재도전은 회복 안내로 연결 |
| adTime | 광고 · 40초 이어하기 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1367) | 외부 광고 UI 연동 상태 시안 · prototype은 성공 보상 경로를 모의 연결 |
| adResult | 광고 · 결과 코인 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1379) | 외부 광고 UI 연동 상태 시안 · prototype은 성공 보상 경로를 모의 연결 |
| adBooster | 광고 · 준비 아이템 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1391) | 외부 광고 UI 연동 상태 시안 · prototype은 성공 보상 경로를 모의 연결 |
| adLife | 광고 · 하트 회복 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1403) | 외부 광고 UI 연동 상태 시안 · prototype은 성공 보상 경로를 모의 연결 |
| adFailure | 광고 불러오기 실패 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1415) | 결과 화면 사례 · 기본보상160 유지 · 추가보상0 · 재시도 가능 |
| adInterrupted | 광고 시청 중단 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1430) | 보상 이벤트 없으면 추가 코인0 · 광고 닫힘만으로 지급 안 함 |
| adLimit | 광고 한도·대기 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1443) | 전체4/일·2/세션·5분 간격과 위치별상한 검사 · 운영가정 |
| adPending | 광고 보상 확인 중 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1456) | 보상 처리 중 이중입력 차단 · requestId 1회 지급 · 임의 추가 지급 없음 |
| boosterReward | 광고 아이템 수령 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1469) | 광고로 재고 +1 · 코인320 유지 · 사용은 준비 화면에서 |
| timeoutUsed | 이어하기 사용 후 시간 종료 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=87-1495) | 이미 +40초 사용 → 재연장 불가 → 실패 확정 |
| settings | 설정 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1171) | 소리·진동·효과 감소 / 재학습 / 계정·개인정보 접근 |
| collection | 아이템·의상 도감 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1215) | 0하트/오프라인에서도 열람 · 효과와 보유량 / 의상 공정 안내 |
| offline | 오프라인 안내 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1266) | 로컬 플레이 가능 · 광고/계정백업만 불가 · 하트 무료회복 계속 |
| saveFailed | 결과 저장 실패 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1280) | 확정 결과를 메모리에 보관 · 저장 성공 전 광고 진입 차단 |
| restore | 앱 복귀·중단된 판 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1293) | 비정상 종료·로딩 실패 하트 차감 없음 · 정상 백그라운드 복귀는 일시정지 |
| restoreTimeout | 시간 종료 상태 복구 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1306) | TIMEOUT_PENDING 복원 · 보상 중복 지급/조기 하트 차감 방지 |
| backupInvite | 진행 백업 권유 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1319) | 2차 계정 기능 출시 후 EP01-12 첫1성 완료 시 1회 제안 |
| login | 선택 로그인 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1335) | 2차 확장 화면 · 실제 인증은 제공사 시스템 UI · MVP에서는 숨김 |
| loginPending | 계정 연결 중 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1364) | 외부 인증 → 결과 대기 · 취소 시 로컬 기록 유지 |
| loginSuccess | 계정 연결 완료 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1377) | 인증 성공·백업 완료 상태 예시 · 실제 계정정보는 표시명/마스킹 |
| loginFailure | 로그인 실패·취소 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1392) | 로그인 실패가 플레이나 로컬 기록을 막지 않음 |
| conflict | 저장 기록 충돌 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1407) | 자동 덮어쓰기 없음 · 두 기록 요약 → 선택 → 재확인 |
| confirmDevice | 기기 기록 선택 확인 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1442) | 백업 병합 정책 확정 전 수동 선택 제안 |
| confirmCloud | 계정 기록 선택 확인 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1456) | 기기 로컬 덮어쓰기 재확인 · 상세 병합/복원 정책은 2차 결정 |
| account | 계정·백업 관리 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1471) | 계정 기능 2차 확장 · 로그인/백업 상태에 따라 항목 변경 |
| logout | 로그아웃 확인 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1504) | 로그아웃 후 게스트 유지 · 로컬 기록 삭제 안 함 |
| deleteConfirm | 계정 삭제 확인 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1519) | 계정·클라우드 삭제 범위와 처리기간은 출시 정책 확인 필요 · 화면 구조 제안 |
| deleteDone | 계정 삭제 요청 접수 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1544) | 실제 삭제 완료/유예 정책은 서비스 구현 시 적용 · 게임은 게스트로 |
| adRepeat | 광고 · 재도전 코인 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1554) | 재도전 기본25의50%=13(반올림) · 새 별 보너스 제외 |
| resultRepeatBonus | 재도전 광고 보너스 수령 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=88-1564) | 기본25+새 별40+광고13 =78 · 4성/700점 유지 |
| mapAfter | 클리어 후 다음 맵 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=91-1219) | 클리어 후 기록·다음 맵 해금 상태 · 최고 별은 저장 데이터로 표시 |
| firstMap | 첫 맵 완료 후 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=91-1415) | 클리어 후 기록·다음 맵 해금 상태 · 최고 별은 저장 데이터로 표시 |
| map2Start | EP02 해금 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=91-1625) | 클리어 후 기록·다음 맵 해금 상태 · 최고 별은 저장 데이터로 표시 |
| nextPrep | 01-09 · 반짝 단추 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=91-1837) | 60맵 마스터 EP01-09 반영 · 장식 공정 최초 추가 |
| prepRecovered | 01-08 · 왕실 조끼 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=91-1872) | 하트 회복 후 진입 허용 · 시작 시 차감 없음 |
| ep2Prep | 02-01 · 파란색은 싫어! | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=91-1907) | 60맵 마스터 EP02-01 반영 · 변경 주문 예고 |
| ep2Play | EP02 주문 변경 예고 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=91-1942) | 변경 예고→확정→새 주문 재료 선택 · 수치 예시 |
| changeOrder | 변경 주문 확인 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=91-1976) | 색상 변화는 글자·아이콘으로 함께 표시 · 재료 재선택 |
| materialMismatch | 재료 불일치 피드백 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=91-2010) | 잘못된 재료는 작업 시작 안 함 · 자동 소모 없음 |
| craftPaused | 작업대 이탈·재개 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=91-2044) | 작업대를 벗어나면 진행 유지 · 재접근 시 이어서 작업 |
| decorate | 단추 장식 공정 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=91-2080) | EP01-09부터 조건부 장식 공정 · 생략하면 완성품 판정 불가 |
| tutPause | 튜토리얼 일시정지 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=91-2113) | 독립 연습 · 하트/별/정규 60맵 계산에서 제외 |
| cutReady | 가위 보유·사용 선택 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=91-2131) | 구매/광고 지급 후 공통 진입 · 보유량 저장, 시작 시 1개 차감 |
| playCutBoosted | 재단 가속 효과 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=91-2149) | CUT20 발동 · 30초 잔여 표시 · 보유1→0 |
| resultBonus1 | 1성 광고 보너스 수령 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=91-2184) | 별·점수 유지 · 첫 클리어 기본100의50%만 추가 |
| resultBonus5 | 5성 광고 보너스 수령 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=91-2216) | 별·점수 유지 · 첫 클리어 기본100의50%만 추가 |
| adResult1 | 광고 · 1성 보너스 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=91-2248) | 광고 시청 성공을 2초 후 모의 · 실제 MAX SDK 아님 |
| adResult5 | 광고 · 5성 보너스 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=91-2259) | 광고 시청 성공을 2초 후 모의 · 실제 MAX SDK 아님 |
| firstNextPrep | 01-02 · 빨강과 파랑 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=92-1793) | 60맵 마스터 반영 · 첫3맵 하트면제 · 주문 색상 선택 첫 적용 |
| firstColor | 주문과 색상 맞추기 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=92-1826) | 첫 색상 선택 예시 · 이 화면은 01-02의 첫 행동 검토용 |
| decorated | 장식 완료·납품 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=92-1859) | 단추 장식 후 완성 판정 · 장식 없음 상태와 비교 |
| resultNext | 장식 맵 완료 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=92-1892) | 01-09 결과 예시 · PAR/보상 표는 개발 전 맵 데이터와 대조 |
| ep2Ready | 변경 주문 재료 확인 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=92-1924) | 주문 변경 예시의 검토 끝점 · 02-01 준비 화면으로 돌아감 |
| guardEvent | 근위병 이동 이벤트 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=92-1957) | EP03 공간 이벤트 제안 · 이동 경로 예고, 작업대와 주문 HUD 유지 |
| result2 | 2성 결과 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=92-1994) | 별 등급 전체1~5 상태 · 보상표:100+새별20×개수 |
| result4 | 4성 결과 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=92-2027) | 별 등급 전체1~5 상태 · 보상표:100+새별20×개수 |

## 검증용 프레임

| 검토 항목 | 크기 | Figma |
|---|---|---|
| 19.5:9 대표 플레이 | 1170 × 540 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=97-1859) |
| 20:9 대표 플레이 | 1200 × 540 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=97-1896) |
| 영문 주문 준비 | 960 × 540 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=97-1933) |

화면 이동은 검토용 프로토타입입니다. 모든 맵의 실제 제작·주문 로직, 저장 및 광고/로그인 서비스는 Unity와 각 서비스에서 구현해야 합니다.
