# git_connect

# git 설치 --> 기본값으로 그대로 설치받음

# 시작버튼에서 git bash 열기(실행)

```
git config --global user.name "sachi"
```

#github 가입시 입력한 이메일과 동일해야한다.

```
git config --global user.name "sachi"

```
# 정보 확인하기
```
$ git config --list

![image](https://github.com/Sary556/git_connect/assets/141836031/058d4ece-3302-484f-bdc0-c98a1d3e44b9)


![화면 캡처 2023-11-02 111028](https://github.com/Sary556/git_connect/assets/141836031/058d4ece-3302-484f-bdc0-c98a1d3e44b9)



✏️ ⬆️의 내용은 컴퓨터에 한번만 설치하면 됨.
----------------
----------------

githtb에 코드 업로드하기

1. 초기화

  ```
  git init
  ```
# .git이라는 폴더가 생성된다.

2. 파일 올리기

  ```
  git add .
  ```

3. 히스토리 만들기

  ```
  git commit -m "내가적고싶은 메세지" 
  ```

# 메세지에는 한글이 가능함
# -m = 메세지의 준말이다

4. Github repository랑 내 로컬 프로젝트랑 연결 ( 깃헙에 프로젝트를 올릴 repository를 먼저 만들어야한다)
# 아래 주소는 깃헙에서 만든 repository에서 복사해서 가져와야한다(repository를 만들며 realme 선택하지 말기)

```
git remote add origin https://gihthub.com/understanding963852/1webstandard.git (대충오리진뭐시기주소가뜨면된다는뜼)
```

5. 잘 연결되었는지 확인(필수 아님)

```
git remove -v
```

6. Github에 자료 올리기

```
git push origin master
```

# 여기까지 하면 Github의 repository에 자료가 올라가 있다.


```
혹은 vs code 의 익스텐션 GitLens를 설치해서 소스제어
![image](https://github.com/Sary556/git_connect/assets/141836031/f0127fec-8903-4fd5-ad27-b1cbe19d3f8c) 소스제어(ctrl+shift+g g)버튼에서 이름을 생성해서 커밋하면 간편하게끝
```


