# A03 화면 목록

2026-11-07. 핵심 게임 경험 48상태이며, 나머지 서비스 예외는 A02/v2.0 정의를 유지합니다.

[게임 경험 시작점](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=112-39) · [연출 구현 명세](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=122-1036)

| ID | 화면 | Figma | 연출·검토 메모 |
|---|---|---|---|
| title | 공방 문을 여는 시작 화면 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=113-2) | 시작 누름70ms + 문 여는 소리 / 배경음은 첫 입력 후 시작 / 메뉴보다 세계가 먼저 |
| hub | 살아 있는 공방 허브 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=113-25) | 큰 메뉴 목록 대신 주문판·연습 책·도구 상자에 진입점 / 첫 목표 1개 |
| brief | 주문 시작 전 기대감 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=113-62) | 주문 봉투160ms 펼침→목표 확인→준비 완료 / 기록·가격보다 오늘 할 일 우선 |
| loading | 천과 실로 이어지는 로딩 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=113-92) | 준비500ms미만이면 생략 · 실제 준비율 사용 · 검토 예시는1.2초 · 가짜 지연 금지 |
| ready | 3·2·1 주문 시작 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=113-123) | 첫 입력 준비1.5초 / 타이머는 시작! 이후 동작 / 준비음3회+시작음 / 입력 잠금 짧게 |
| play | 목표가 보이는 플레이 HUD | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=113-194) | 주문·남은시간·다음별을 분리 / 작업대 근접 강조 / 하트·광고·지갑은 플레이 중 숨김 |
| tutorial | 세계 안에서 배우는 독립 연습 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=113-258) | 설명창 대신 한 행동씩 / 시간·별·하트 평가 없음 / 정상 플레이와 동일한 조작 |
| picked | 원단 집기 반응 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=116-1311) | 120ms 집기·천 마찰음160ms·가벼운 진동10ms |
| cutting | 재단 진행·리듬 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=116-1388) | 진행은 작업대 바로 위 / 가위 소리140ms×2 / 완료 시만 긍정음 |
| cutDone | 재단 완료 반응 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=116-1499) | 완료250ms 튕김 + 체크 / 다음 작업대 강조 / 반복 설명창 없음 |
| sewing | 봉제 진행·기계 반응 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=116-1621) | 기계 왕복 루프2초 / 소리300ms 루프 / 이탈·일시정지 시 즉시 정지 |
| carry | 완성품 회수·납품 유도 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=116-1691) | 완성품을 머리 위에 표시 / 납품대 윤곽 + 방향 신호 / 소리 없이도 구별 |
| delivery | 납품·점수·별 피드백 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=116-1761) | 점수0→300→570 예시 / 칭찬→점수 이동→별 순서 / 추가 콤보 보상 없음 |
| play2 | 두 번째 주문 · 두 번째 원단 고르기 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=116-1920) | 첫 납품 후 다음 행동을 즉시 제시 |
| picked2 | 두 번째 주문 · 원단 집기 반응 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=116-1978) | 120ms 집기·천 마찰음160ms·가벼운 진동10ms |
| cutting2 | 두 번째 주문 · 재단 진행·리듬 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=116-2055) | 진행은 작업대 바로 위 / 가위 소리140ms×2 / 완료 시만 긍정음 |
| cutDone2 | 두 번째 주문 · 재단 완료 반응 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=116-2166) | 완료250ms 튕김 + 체크 / 다음 작업대 강조 / 반복 설명창 없음 |
| sewing2 | 두 번째 주문 · 봉제 진행·기계 반응 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=116-2288) | 기계 왕복 루프2초 / 소리300ms 루프 / 이탈·일시정지 시 즉시 정지 |
| carry2 | 두 번째 주문 · 완성품 회수·납품 유도 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=116-2358) | 완성품을 머리 위에 표시 / 납품대 윤곽 + 방향 신호 / 소리 없이도 구별 |
| delivery2 | 두 번째 주문 · 납품·점수·별 피드백 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=116-2428) | 점수0→300→570 예시 / 칭찬→점수 이동→별 순서 / 추가 콤보 보상 없음 |
| result | 별·보상의 순차적 만족감 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=117-217) | 3성0.25/0.49/0.73초→코인0.95초→다음목표1.6초 / 광고는 축하 후 보조 선택 |
| bonus | 선택 보너스 수령 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=117-365) | 기본 보상50%만 추가 / 160+50=210 / 최고별3 유지 / 중복 콜백 재지급 금지 |
| urgent | 10초 경고의 우선순위 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=117-454) | 타이머만 주황 / 10초1회·3/2/1초 짧은틱 / 화면 전체 점멸·카메라 흔들림 없음 |
| timeout | 시간 종료·호흡 후 선택 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=117-514) | 0초→작업/음악 긴장층 정지→250ms 후 선택 / 선택 대기 중 하트 차감 없음 |
| resume40 | 연장 보상 즉시 확인 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=117-565) | 보상 콜백→+40 숫자 이동→타이머40초 / 주문·작업 상태 복원 / 한 판1회 |
| fail | 실패 이유와 다음 도전 목표 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=117-629) | 비난/강한 버저 없이2음 / 하트4→3은 한 번만 / 최고기록 유지 / 재도전 목표 명시 |
| pause | 정지와 재개 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=117-656) | 시간·작업·SFX루프 함께 정지 / BGM -8dB / 복귀시 중복 완료음 없음 |
| workPaused | 작업대를 떠났을 때 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=117-671) | 재단60%보존 · 멈춘진행바+가위아이콘 / 작업루프 즉시 정지 / 복귀시 재개음1회 |
| slowLoad | 느린 로딩·복구 안내 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=117-731) | 실제 준비3초초과 안내 / 10초초과 재시도·공방 선택 / 보상 확정 전 축하음 재생 금지 |
| adPending | 코인 보너스 확인 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=117-748) | 검토용 광고 성공 모의 / 실제 MAX 보상 콜백에서만 지급·연출 / 닫기만으로 지급 금지 |
| adContinue | 시간 연장 확인 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=117-761) | 검토용 광고 성공 모의 / 실제 MAX 보상 콜백에서만 지급·연출 / 닫기만으로 지급 금지 |
| map | EP01 왕실의 부름 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=119-285) | 직선 목록→실로 연결된 12개 맵 / 해금되는 위치를 직접 강조 / 조건은 이전 맵1성 이상 |
| unlocked | 다음 맵 해금 · EP01 왕실의 부름 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=119-481) | 직선 목록→실로 연결된 12개 맵 / 해금되는 위치를 직접 강조 / 조건은 이전 맵1성 이상 |
| ep2 | EP02 변덕쟁이 임금님 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=119-761) | 직선 목록→실로 연결된 12개 맵 / 해금되는 위치를 직접 강조 / 조건은 이전 맵1성 이상 |
| ep3 | EP03 근위병 대소동 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=119-948) | 직선 목록→실로 연결된 12개 맵 / 해금되는 위치를 직접 강조 / 조건은 이전 맵1성 이상 |
| ep4 | EP04 왕궁 무도회 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=119-1135) | 직선 목록→실로 연결된 12개 맵 / 해금되는 위치를 직접 강조 / 조건은 이전 맵1성 이상 |
| ep5 | EP05 이웃국가의 귀빈 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=119-1322) | 직선 목록→실로 연결된 12개 맵 / 해금되는 위치를 직접 강조 / 조건은 이전 맵1성 이상 |
| locked | 잠긴 맵·해금 조건 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=119-1509) | 잠금음 짧은 나무 톡 / 비난·붉은 오류 연출 없음 / 해야 할 다음 행동 제공 |
| nextBrief | 해금 보상은 새로운 행동 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=119-1524) | EP01-09 반짝단추 · 다음 목표를 구체화 / 12맵 마스터와 일치 / 별 추가 보상 신설 없음 |
| settings | 소리와 효과 조절 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=119-1539) | BGM·SFX·진동 개별 제어 / 효과 줄이기: 플래시·흔들림·동전비행 제거 / 중요 정보는 유지 |
| boosters | 도구 상자에서 선택 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=119-1562) | 복잡한 상점 대신 사용할 도구3개 / 보유량과 효능을 같은 위치 / 가격 제안은 추가하지 않음 |
| tutPick | 2 / 5 · 원단 집기 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=120-1015) | 독립 연습 / 제한시간·별·하트 차감 없음 / 누름→반응→다음 행동만 제시 |
| tutCut | 3 / 5 · 재단 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=120-1045) | 독립 연습 / 제한시간·별·하트 차감 없음 / 누름→반응→다음 행동만 제시 |
| tutSew | 4 / 5 · 봉제 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=120-1083) | 독립 연습 / 제한시간·별·하트 차감 없음 / 누름→반응→다음 행동만 제시 |
| tutDeliver | 5 / 5 · 납품 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=120-1119) | 독립 연습 / 제한시간·별·하트 차감 없음 / 누름→반응→다음 행동만 제시 |
| tutDone | 연습 완료·자신감 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=120-1148) | 작은 완료음·체크 / 게임 재화나 정규맵 별을 지급하지 않음 / 독립튜토리얼 유지 |
| wrongMaterial | 잘못된 재료·바로 고치기 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=120-1166) | 원인과 수정 행동을 같은 곳 / 재료 자동소모 없음 / 160ms 작은 흔들림+짧은 나무음 |
| reduced | 화면 효과 줄이기 | [열기](https://www.figma.com/design/GUBBsgjCI1Fb8SEq9aonvi?node-id=120-1231) | 별·금액·다음목표 동일 / 비행·확대·화면흔들림 제거 / 120ms 이하 페이드만 허용 |
