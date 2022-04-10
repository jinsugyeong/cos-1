# GIT 명령어 정리
<br>   

[Github로 팀프로젝트 협업하기](https://everyday-com-eat.tistory.com/98)

1. 파일 더하기
	```
	git add .
	/*전체 파일*/   
	git -f add *
	```   

2. 커밋, 메세지
	```
	git commit -m ""
	```      
	
3. 커밋 취소
	```
	git rm *
	or 
	git reset *
	```   

4. 푸쉬   
	```
	git push origin master
	
	//강제
	--force
	```
	
5. user.name, user.email 설정
	```
	git config --global user.name "your_name"
	git config --global user.email "your_email"
	```

6. clone 만들기
	```
	git clone 주소 폴더이름(없어도됨)
	git checkout -b 브렌치이름   
	git pull origin master   
	git add .
	git commit -m "first commit"
	git push origin 브렌치이름
	```   
   
7. push까지 한 commit 되돌리기(revert, reset)
	```
	git revert [되돌아갈 commit 아이디]
	(revert 한 내역까지 모두 기록됨)
	
	git reset [되돌아갈 commit 아이디]
	(되돌아갈 commit 아이디 위로의 history까지 모두 삭제됨)
	```
