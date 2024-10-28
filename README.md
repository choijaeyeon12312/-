파이썬 컬링 게임 만들기
게임 제목: 알파고랑 컬링고?

<게임에 대한 간단한 소개>

 스페이스바를 누르는 시간에 따라 강약조절이 되어서 4번씩의 시도 끝에 원에 더 많은 스톤이 남은 스코어를 계산하여 점수가 높은 플레이어가 승리합니다.
플레이어는 빨간 스톤을 던지고 상대방은 컴퓨터로 노랑스톤을 랜덤으로 강약을 조절하여 스톤을 굴립니다.

<class에 대한 언급>

레드팀 옐로우팀 당 4번씩의 스톤을 던지는데 각각의 스톤마다 class화 하여 총 스톤객체가 필요하고 각각의 스톤마다 충돌처리를 필요로 하게됩니다.
(추가)각라운드 마다 점수집계 ,누구의 차례인지 나타내는 게임상태를 업데이트하는 game 클래스도 필요로합니다.
누구의 차례인지,남은 스톤은 몇개있는지,현재 점수 등을 나타내는 UI도 필요로 합니다.

이 게임에 스킬,아이템등 재미요소를 추가하지 않은 이유는, 스포츠는 추가적인 재미요소 없이도 게임으로써 충분한 재미를 줄 수 있고, 스포츠는 추가적인 요소 없이 최대한 실제와 비슷하게 구현되어야 더 몰입감있고 즐길 수 있다고 생각이 되어서 추가하지 않았습니다. 


<일정>
1주차-게임 리소스 수집 및 편집,시작 화면 구성
2주차- 게임플레이 화면 구성 및 스톤 이미지 적용
3주차-  스톤별 충돌처리(자연스럽게 밀리기)
4주차- ui 추가
5주차- 사운드 추가
6주차-보완,마무리


<수업에서 추가로 다루었으면 하는 부분>

우선 스톤끼리 충돌하였을때, 앞으로 나아가던 스톤은 충돌하면 점차 속도가 줄어들다가 멈추고, 앞에 서있던 스톤은 방향이 바뀌어 이동하게 되는 액션을 주고싶은데 어렵게 느껴졌습니다.
또 점수계산적인 부분에서  게임이 끝난 후 각각의 원 안에 있는 스톤에 위치에 따라 점수를 계산하고 누가 이겼는지 승패를 겨룰 수 있는 방법이 있는지 알고 싶습니다.

