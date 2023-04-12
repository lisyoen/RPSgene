# RPSgene
Rock Paper Scissors gene game server
https://docs.google.com/presentation/d/1ECB5zgLFHZ1e9QwkAz0lQ1wzsbswbC-IXnoztN8N7gM/edit?usp=sharing

# 개요
- 전사 개발자들이 즐길 수 있는 경쟁 플랫폼 구축
- 간단한 게임 규칙을 REST API 로 개발해 개인PC 에서 동작시킬 수 있도록 구성
- 사내 및 사외에서 경쟁상황을 확인할 수 있도록 하여 흥미 증진
# 내용
- 참여자 각자가 가위바위보를 낼 수 있는 REST API 를 구축/운영한다.
  - 개발 언어/프레임워크는 지정하지 않음
- 참여자는 경기장에 참가 신청을 한다.
  - 가위바위보 REST API URL 및 참여자 이름 등록
- 경기장 플랫폼은 무작위로 2명의 참여자를 선정해 가위바위보를 시킨 후 결과를 도출한다.
- 결과에 따라 승자는 어드벤티지를, 패자는 패널티를 받는다.
  - 점수 혹은 생존
- 정기적으로 경기가 이루어지며 결과는 웹페이지를 통해 공개된다.
## 준비
### 경기장 플랫폼 개발
- Back-end
  - 참여자 정보 CRUD
  - 경기결과 C
- Front-end   
  - 참여자 등록/갱신/탈퇴
  - 경기현황 모니터링
  - 경기이력 조회
  - 참여방식 안내
### 경기장 플랫품 운영
- 내 업무용 PC 또는 부서 서버 중 1대 활용
  - 윗분들 설득 되면 사내 서버 운용 가능할듯.
