/*

수정 : 
딜레이 0.25초 => 0.4초
실패 확률이 점점 큰 폭으로 감소 1.5 * (1 + (level - 1) / 10) => 1.7 * (1 + (level - 1) / 10)
게임 오버 시 정보가 초기화되지 않던 문제를 수정
아이템 사용 시 레벨이 올라가던 버그를 수정
UI 개편

추가 : 
강화 실패시 초기화를 막아주는 아이템 추가
최고 기록(레벨,키)을 추가
게임 오버 팝업 추가
특정 레벨 달성 시 아이템 지급 추가

*/
