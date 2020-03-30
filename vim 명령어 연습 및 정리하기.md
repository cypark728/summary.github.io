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

![image](https://user-images.githubusercontent.com/48200520/77898439-15963000-72b6-11ea-9e4a-d4bd10154480.png)![image](https://user-images.githubusercontent.com/48200520/77898439-15963000-72b6-11ea-9e4a-d4bd10154480.png)

위의 명령어를 입력하면 아래에 INSERT가 생기는 것을 알 수 있다. 그러면 insert(edit) mode에 진입한 것이다. 

### 지우기
*x 한글자 지우기

*dw 현재 커서부터 단어의 끝까지 지우기

*dd 한줄 지우기 (tmi.d를 두번누를때 두번째 d를 꾹 누르면 한줄씩 계속 지워진다.)

*숫자dd 원하는 숫자 크기만큼 줄 지우기





