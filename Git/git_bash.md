# terminal 명령어 정리
<br>

1. 파일 더하기
	```
	git add .
	```   

2. 커밋, 메세지
	```
	git commit -m ""
	```      
	
	
2-1. 커밋 취소
	```
	git rm *
	or
	git reset *
	```   

3. 푸쉬   
	```
	git push origin master
	
	//강제
	--force
	```
	
4. user.name, user.email 설정
	```
	git config --global user.name "your_name"
	git config --global user.email "your_email"
	```

5. clone 만들기
	```
	git clone 주소 폴더이름(없어도됨)
	git checkout -b 브렌치이름   
	git pull origin master   
	git add .
	git commit -m "first commit"
	git push origin 브렌치이름
	```
