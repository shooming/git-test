# GIT 명령어 정리

```git
git init
```
- 이곳이 git 저장소가 될것이라고 git에게 알려주는 초기화 명령어이다.

------

```git
git add (commit시킬 파일, 폴더)
```
- staged 상태로 만드는 과정이며 .을 쓰면 현재폴더 아래 모든 파일,폴더를 add한다.

------

```git
git commit -m ""
```
- git을 commit하여 committed 상태로 만든다 -m은 바로뒤에 메시지를 사용하겠다는 뜻이다. 옵션이 없으면 내장 글쓰기 에디터를 사용한다.

------

```git
git push orgin (push할 브랜치)
```
- commit한 내용을 원격저장소에 보내기위한 명령어이다. git push는 원격저장소로 보내겠다는 뜻이고 orgin은 원격저장소의 별명인데 default로 origin을 많이 사용한다.
그뒤는 push할 local branch의 위치이다.