# GIT command 

> git 기본 명령어

## init
현재 위치에 .git 폴더를 생성 (ls-a와 ls 명령어의 차이)

``` bash

git init

```
*개발 생태계에서 책이라는건 버전이 느린 데이터들이기 때문에 검색을 통해서 기술을 만든 회사의 공식 문서를 보는 것을 추천

## add
띄어쓰기 조심 ! / git add 할 때 위치를 확실히 하기 (예를들어 상위 위치에서 깃을 추가하는거랑 하위 위치에서 깃을 add하는 거랑 충돌할 수 있기 때문. 내가 관리하고자 하는 위치에서만 깃을 add 하면 됨) / git 추가하다가 충돌하면 깃을 지우면 됨 (rm -r)

```bash
git add .
```
## status
- 현재 git 상태 확인

```bash
git status
```

## commit
git commit만 쓰면 author identity를 물어봄
git config --global user.email로 "이메일"


    staging area에 올라간 내용을 스냅샷 찍기

        -  `-m` 옵션을 통해 커밋메세지를 바로 입력 가능
    

    ```bash
    git commit -m "first commit"
    ```

