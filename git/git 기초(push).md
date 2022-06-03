### 1. git 으로 관리 시작

-> 디렉토리당 한번만
주의! 홈폴더나 바탕화면 x

```bash 
$ git init
```



### 2. 파일 상태 확인

```bash 
$ git status
```



### 3. 무대위로 올리기 (staging area)

```bash
$ git add 폴더명
```



### 4. 변경사항을 기록 즉, 사진 찍기
(vim 빠져 나오는 것 esc + :q )

```bash
$ git commit -m "커밋 사유"
```



### 5. config 설정 
-> 한번만!,  git에게 내가 누군지 알려주기 

```bash
$ git config --global user.email "you@example.com"
$ git config --global user.name "Your Name"
$ git config --global --list #설정 확인
```



### 6. 커밋의 내역 확인

```bash
$ git log
# 또는
$ git log--oneline
```



### 7. 커밋들을 비교하기

```bash
$ git diff 해쉬값 해쉬값
```



### 8. github와 연결
url은 깃허브 레퍼지토리 주소 

```bash
$ git remote add origin URL
$ git remote -v
```



### (필요시) remote 삭제

```bash
$ git remote rm origin
```



### 9. github에 local commits 올리기

```bash
$ git push origin master
```

