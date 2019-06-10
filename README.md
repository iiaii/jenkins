# #소검/테스팅

1. Time Keeping Mode

- Set Time

문제1) 연도1이 99가 넘어가면 모든 값이 이상한 값으로 갑자기 바뀌어 버리고, 원하는 날짜와 시간을 맞출수 없음. (선택된 값이 아닌 다음 값이 같이 변경되기도 하며 월, 일 ,시,분,초 에서 나올수 없는 단위로 바뀌기 시작함, 원하는 시간 설정이 불가능해짐)

[image:65C76DBA-BC46-4C01-8004-16E593B486C7-38294-0001FD20BEA5BAED/스크린샷 2019-05-28 오후 6.50.23.png]

- Set Hour Format

문제1) 00시 59분 59초 이전부터 01시를 넘어간 뒤로 A버튼이 더 이상 작동하지 않음.

[image:23FF9F24-A8DD-42A8-989D-D31CB6C41216-38294-0001FE9F4C3DD122/스크린샷 2019-05-28 오후 7.17.47.png]

2. WatchTimer Mode
 
+ Activate Timer

+ Set Timer

- Notify Finish Timer

문제1) 타이머 30초 설정 후 모드변경하여 타이머를 제외해도 30초 후에 알람이 울림.

문제2) 타이머가 0이되어 알람이 울리고, 알람을 멈추면 설정한 타이머 시간으로 다시 채워진다는 내용이 스펙에 나와있지 않음

+ Pause Timer

+ Reset Timer

3. Stopwatch Mode

+ Activate Stopwatch

+ Pause Stopwatch

+ Reset Stopwatch

5. Alarm Mode

+ Set Alarm

- Reset Alarm

문제1) 수정모드에서 D버튼을 눌러도 enabled된 알람이 disabled 상태로 바뀌지 않음. (00시00분00초 상태에서 En이 활성화됨)

문제2) 스펙에서는 C버튼을 눌러 수정모드 접근 후 D버튼을 눌러 0으로 리셋하고 C버튼으로 저장해야한다고 했지만, C버튼을 눌러 수정모드 접근 후 D버튼을 누르면 0으로 리셋되고 수정모드를 벗어남.

+ Enable Alarm

+ Disable Alarm

+ Notify Alarm

+ Change alarm page

7. D -day Mode

- Set D-day

문제1) 연도1이 99가 넘어가면 분을 제외한 모든 값이 이상한 값으로 갑자기 바뀌어 버리고, 원하는 날짜와 시간을 맞출수 없음. (선택된 값이 아닌 다음 값이 같이 변경되기도 하며 월, 일 에서 나올수 없는 단위로 바뀌기 시작함, 원하는 시간 설정이 불가능해짐)

[image:1DE580DF-67DD-4192-BAD2-B8A5B2E24732-38294-000201A82849FB48/스크린샷 2019-05-28 오후 8.13.24.png]

문제2) 종료일이 시작일 보다 이전으로 선택 가능하며 음수값으로 표기됨.

[image:624F7C9B-F151-49DB-98FF-10F57B8FF211-38294-00020200A6761102/스크린샷 2019-05-28 오후 8.19.44.png]

문제3) 4자리 이상(9999이상)의 d-day는 표현이 안됨. (앞의 자리가 제외되는듯 함)

문제4) 무엇이 시작일이고 무엇이 종료일인지 구별하기 어려움.

+ Reset D-day

+ Notify D-day

- Set D-day Format

문제1) 시작일과 종료일이 같고, 미래 날짜로 설정한 경우 d-day에서는 잔여일이 잘 나타나지만 % 에서는 ‘done’으로 표시됨.

9. IntervalTimer

+ Enable Interval Timer

- Disable Interval Timer

+ Set Interval Timer

- Reset Interval Timers

문제1) 스펙에서는 C버튼을 눌러 수정모드 접근 후 D버튼을 눌러 0으로 리셋하고 C버튼으로 저장해야한다고 했지만, D버튼을 누르면 0으로 리셋되고 수정모드를 벗어남.

- Notify Finish Interval Time

문제1) 타이머 30초 설정 후 모드변경하여 
타이머를 제외하면 알람이 울리는지 확인한다
모드변경으로 제거된 기능이므로
알람이 울리지 않을 것이다
타이머 30초 설정 후 모드변경하여 
타이머를 제외해도 30초 후에 알람이 울림
FALSE


11. Mode Setting

- Change Mode

문제1) 스펙과 달리 C버튼으로 모드 변경시 Beep이 출력되지 않음.

+ Set Mode

13. Edit Mode

+ Mute Beep
