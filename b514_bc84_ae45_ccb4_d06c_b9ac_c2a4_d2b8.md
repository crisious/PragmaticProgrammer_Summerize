# 디버깅 체크리스트

* 보고된 문제가 내재하는 버그의 직접적 결과인가 아니면 단순한 증상일 뿐인가?
* 버그가 정말로 컴파일러에 있나? OS 에 있나? 혹은 코드에 있나?
* 이 문제를 동료에게 상세히 설명한다면 어떻게 말하겠는가?
* 의심이 가는 코드가 단위 테스트를 통과한다면, 테스트는 충분히 완전한 것인가? 이 데이터로 단위 테스트를 돌리면 무슨 일이 발생하는가?
* 이 버그를 야기한 조건이 시스템의 다른 곳에도 존재하는가?