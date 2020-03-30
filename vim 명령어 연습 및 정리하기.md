# vim 명령어 연습 및 정리하기
## Vim 의 모드
### *일반 모드(Normal mode) 또는 명령모드 (Command mode)
입력하느 모든 키는 명령을 숭행한다. 
### *명령줄 모드(Comman Line mode)
화면 하단에 :(콜론) 프로프트에 명령문장을 입력하거니/프로포트에 단어를 입련한다. 
### *편짐/입력 모드(Insert mode)
입력하는 모든 키는 문서의 내용을 작성한다. 
### *비주얼/선택 모드(Visula mode)

## Vim 명령어
### Vim 파일 만들기
$ vim hello.txt

이 명령어를 입력하면 hello.txt가 만들어 집니다. 이미 hello.txt파일이 있을경우 hello.txt파일을 열게 됩니다. 
![image](https://user-images.githubusercontent.com/48200520/77897882-3ca03200-72b5-11ea-8e13-991ecc7c7f04.png)
### insert(edit) mode 진입 키
*i 현재 커서의 앞에서 편집 시작

*a 현재 커서의 다음부터 편집 시작

*A 현재 커서 맨 끝으로 커서 이동하고 펹비 시작

*o 현재 커서 아래에 새로운 줄을 추가하고, 편집 시작

*O 현재 커서 위에 새로운 줄을 추가하고, 편집 시작

![image](https://user-images.githubusercontent.com/48200520/77898439-15963000-72b6-11ea-9e4a-d4bd10154480.png)

위의 명령어를 입력하면 아래에 INSERT가 생기는 것을 알 수 있다. 그러면 insert(edit) mode에 진입한 것이다. 

### 지우기
*x 한글자 지우기

*dw 현재 커서부터 단어의 끝까지 지우기

*dd 한줄 지우기 (tmi.d를 두번누를때 두번째 d를 꾹 누르면 한줄씩 계속 지워진다.)

*숫자dd 원하는 숫자 크기만큼 줄 지우기
### undo/redo
*u 마지막 명령 취소 (tmi. u 를 꾹 누르면 계속 마지막 명령을 취소한다.)

*U 해당 줄 전체의 수정사항 취소

![image](https://user-images.githubusercontent.com/48200520/77900284-ce5d6e80-72b8-11ea-889c-a7409cde61f3.png)
![image](https://user-images.githubusercontent.com/48200520/77900290-d0bfc880-72b8-11ea-8049-4cb8e92794b9.png)ㅇ

dd명령어로 삭제함 부분을 u 명령어로 복구한 모습이다. 

### 내용 변경
*r 글자 하나를 변경할 때 사용

*cw 다어의 일부나 전체 변경할 떄 사용(해당 단어 삭제 후 입력)

*c$ 해당 줄 전체를 변경할 때 사용(한 줄 삭제 후 입력)

### 붙여넣기
*p 마지막 지운 정보를 현재 커서 다음 위치에 붙여넣기

### 빠르게 이동
* 줄번호 + shift + g 해당 줄번호로 이동

*shift + G 파일에서 마지막 라인 이동

*ctrl + g 현재 커서의 위치와 파일 상태를 볼 수 있음

![image](https://user-images.githubusercontent.com/48200520/77901587-ce5e6e00-72ba-11ea-8316-a105ef9a0b1f.png)

ctrl + g 명령어로 현재 커서의 위차와 파일 상태를 확인하는 모습이다. 

### 저장하고 나가기
* ZZ 현재 파일을 저장하고 vim 종료

![image](https://user-images.githubusercontent.com/48200520/77901871-4a58b600-72bb-11ea-8869-c2b881406561.png)

ZZ 명령어로 잘 저장된 모습이다. 

### 글자(단어) 찾기
*/글자(단어) 아래쪽으로 글자(단어) 찾기

*?글자(단어) 위쪽으로 글자(단어) 찾기

*n 아래쪽으로 방금 찾은 단어 또 찾기(next)

*shift + n 위쪽으로 바윽ㅁ 찾은 단어 또 찾기


![image](https://user-images.githubusercontent.com/48200520/77902605-6dd03080-72bc-11ea-8b37-7dfe3d87390c.png)

?very 명령어를 사용하여 위쪽으로 글자를 찾아 가장 아래쪽에 very를 찾은 모습이다. 


