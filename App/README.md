# Rainbow - Application

## Project Explanation
라즈베리파이, 데이터베이스, Firebase 등을 사용하여 공부시간을 효과적이고 직관적으로 볼 수 있는 어플리케이션

<동작화면>

다음 화면으로 구성된다.

### 달력 화면
<img width="200" src="https://user-images.githubusercontent.com/22738293/97805140-9af02180-1c97-11eb-808b-bfd120d9ca50.jpeg">
- 달력 형태로 공부 여부를 보여준다.
- 한달 전까지의 공부 기록을 보여준다.
- 하루하루의 공부여부를 요일별로 빨강/주황/노랑/초록/파랑/남/보라색으로 나타낸다.  

### 지난 한 달간의 무지개 성적 화면
<img width="200" src="https://user-images.githubusercontent.com/22738293/97805150-aa6f6a80-1c97-11eb-8c26-21e31a00dd97.jpeg">
- 지난 한달 동안, 일주일 별로 나누어 무지개 성적을 알려준다.
- 7이 모두 성공하였으면 무지개, 4일 이상 성공하였으면 반무지개, 4일이하 성공하였으면 먹구름을 받는다.

### 일자 화면
<img width="200" src="https://user-images.githubusercontent.com/22738293/97805146-a3485c80-1c97-11eb-9d20-1c2c1a7aff27.jpeg">
- 달력 화면에서 일자를 선택하면, 선택한 일자의 일자 화면으로 넘어 간다.
- 일자화면에서는, 그 일자의 총 공부량과 핸드폰 사용량을 나타내준다.
- 총 공부량은 텍스트 뿐만 아니라, progress bar 형태로도 보여줘 한 눈에 알기 쉽게 한다.

### 목표 시간 설정 화면
<img width="200" src="https://user-images.githubusercontent.com/22738293/97805148-a6dbe380-1c97-11eb-90eb-89e29e481752.jpeg">
- 달력 화면에서 설정아이콘을 누르면, 목표 시간 설정 화면으로 넘어 간다.
- 타임피커를 통해 목표 시간을 설정할 수 있고 해당 목표시간을 텍스트 뿐만 아니로 토스트 메세지로 명시한다.

### 푸시 알림
- 매일 자정에, 사용자는 자신의 공부시간에 대한 알람을 받는다.

prolificinteractive/material-calendarview
사용함
