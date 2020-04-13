# Git

## git add
내 git에 파일들을 추가하는 명령어이다. 


## git status
내 git의 상황을 확인할 수 있는 명령어이다. 


![image](https://user-images.githubusercontent.com/48200520/79125165-a271db00-7dd8-11ea-8fe6-d9f2d5e7736a.png)



## git commit
내 git에 commit 하는 명령어이다. -m을 사용하여 간단한 메모를 할 수 있다. 

![image](https://user-images.githubusercontent.com/48200520/79125107-89692a00-7dd8-11ea-8c5a-fe87a85d845d.png)


## git remote add orgin remote
remote repository 의 주소를 등록하는 명령어이다. 


## git push -u origin master
등록된 주소에 push하는 명령어이다. 


![image](https://user-images.githubusercontent.com/48200520/79125246-cfbe8900-7dd8-11ea-84cd-ff97c79b2f98.png)


## git log 
지금까지 git 을 사용한 로그를 확인할 수 있다. 


## git checkout
마지막으로 commit 한 버전으로 돌아간다.


# 시나리오
## 이미 올라간 파일 수정해서 다시 올리기
### 파일을 수정한다. 
### git에 파일을 추가한다

![image](https://user-images.githubusercontent.com/48200520/79127690-4fe6ed80-7ddd-11ea-8df7-44a3ed5838ed.png)


git status를 통해서 main.c가 수정된 것을 확인할 수 있다. 

### 수정한 파일 commit하기


![image](https://user-images.githubusercontent.com/48200520/79128155-02b74b80-7dde-11ea-8c9c-5edff12e8952.png)




### 등록된 주소에 push 하기


![image](https://user-images.githubusercontent.com/48200520/79127786-7442ca00-7ddd-11ea-9f5e-dfb4b90aad4b.png)


push가 잘 된것을 확인 할 수 있다. 

### commit된 파일 비교하기


![image](https://user-images.githubusercontent.com/48200520/79127872-8f153e80-7ddd-11ea-9f53-b1f20f64956d.png)

printf("something fixed"); 가 printf("fix something"); 으로 바뀐것을 알 수 있다.

