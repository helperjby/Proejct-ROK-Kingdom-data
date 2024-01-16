# ROK-Kingdom-data

### 0. 프로젝트 개요
* 목표: 모바일 게임 Rise of kingdoms의 데이터기반의 조직 운영을 위한 지표설정, 수집, 전처리, 대시보드, 시각화
* 배경:
  * 특정 기준에 따라 2,000여개가 넘는 서버(=왕국) 중 4 ~ 12개의 왕국이 매칭되어 일정기간 동안 전쟁을 통해 승패를 가리는 게임 시스템(=kvk)
  * kvk에서 승리한 왕국은 유니크한 보상을 획득하며, 유저들은 왕국간 이민이 시스템적으로 허용되어 있음.
  * 왕국의 건전한 운영과 구성원들이 납득 가능함을 충족하는 데이터 기반의 지표설정(기여도 측정) 및 그에 기반한 보상분배가 필요해짐
    * 건전한 운영: 유리한 kvk 매칭구도, 왕국원들의 전쟁 수행 퍼포먼스를 유지하기 위한 조직관리
    * 보상분배: 객관적인 기여도에 따라 게임 내 한정적인 재화를 분배
   
### 1. 진행 프로세스 및 담당파트
|프로세스|작업자|작업내용|
|---|---|:---:|
|1. 지표 설정|장병용|매칭된 상대 왕국과 외교구도, 이전 kvk에서의 데이터를 고려하여 1인당 달성 KPI 산출|
|2. 데이터 수집|엔젤,셋잇|전체 왕국인원의 프로필 및 KVK 결과 레포트에서 기여도 책정에 필요한 데이터 수집|
|3. 데이터 전처리|장병용|수집된 데이터의 전처리 및 가공|
|4. 대시보드 생성|장병용,셋잇|산출된 기여도 공개, 유저들이 쉽게 접근 가능한 대시보드 제작(lookerstudio & tableau)|
|5. 시각화 레포트|장병용|데이터의 시각화를 통해 왕국 퍼포먼스의 스토리텔링|


### 2. 아웃풋
2023.1월 ~ 현재까지 총 5회의 kvk에 대한 데이터 기반 기여도 산출

1. kvk 대시보드
 - <a href="https://lookerstudio.google.com/u/0/reporting/22d861df-6b39-47a3-a6ec-24a18f846b09/page/9juDD?s=rzTs5uTIfW0" target="_blank">lookerstudio를 활용한 기여도 대시보드(현재 페이지 열림 주의)</a>
![image](https://github.com/helperjby/Proejct-ROK-Kingdom-data/assets/69462995/ac8cf7fc-bd33-4ae2-84d5-5e5fc1d33d66)

 - [Tableau를 활용한 개인 kvk성적 대시보드(현재 페이지 열림 주의)](https://public.tableau.com/app/profile/.73985057/viz/ROK1718kvkhistory/1_1?publish=yes)
![image](https://github.com/helperjby/Proejct-ROK-Kingdom-data/assets/69462995/3aab256c-3ea9-457b-aa30-a89324e776fa)

2. [왕국 시각화 레포트(현재 페이지 열림 주의)](https://helperjby.tistory.com/45)
![image](https://github.com/helperjby/Proejct-ROK-Kingdom-data/assets/69462995/d9797f3c-3f91-459a-83b9-92fcb6d0caea)


3. 전처리와 시각화.ipynb 파일

