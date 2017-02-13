#Git 정리
1. Git 기본명령어
2. Git 팁

## Git 기본 명령어
	1) git config --global --list : 현재 설정정보 조회
	2) git config --global user.name "사용자명" : 이름 설정(필수)
	3) git config --global user.email "email" : 이메일 설정(필수)
	4) git config --global color.ui “auto” : 표시 메세지 컬러로 설정
	5) git status : 현재 커밋되지 않은 변경사항 조회
	6) git add <file> : 변경/수정 후 스테이징영역으로 올려준다.
	7) git commit -m '메세지' : 스테이징 영역에 있는 파일을 커밋하며 메세지를 남겨 변경이유를 기록한다.
	8) git push : 원격저장소에 파일을 올린다. 변경사항을 로컬저장소에 있는 파일과 합친다.
	9) git pull : 원격저장소에서 파일을 가져온다. 변경사항을 로컬저장소에 있는 파일과 합친다.
	10) git clone : 원격저장소에서 파일을 복사해온다.
	11) git merge : 파일을 합친다.
	12) git checkout <브랜치/태그명> : 작성한 브랜치 혹은 태그로 작업트리를 변경한다.
	12-1) git checkout -b (브랜치/태그명) : 브랜치가 없을경우 브랜치를 생성하는 것과 동시에 작업트리를 변경한다.
	13) git branch <name> : 작성한 이름의 브랜치가 생성된다.
	13-1) git branch : 이름을 입력하지 않을 경우 생성된 브랜치를 조회한다.
	(-r을 입력할 경우 원격저장소의 브랜치를 확인할 수 있다.)

## Git 팁
	1) merge 혹은 push 할 때 충돌이 일어나 에러가 생길경우 수동으로 합쳐야한다.
	2) 원격저장소로 push하기 전 pull을 이용하여 원격저장소의 master브랜치에 있는 파일과 충돌이 있는지 미리 확인하는 것이 좋다.
	3) 업무한 파일을 업로드할 때 바로 원격저장소의 master브랜치로 업로드하는 것은 좋지 않다.
	4) git config --global alias.<단축명령어> <원래명령어> : 원래 존재하는 git 명령어를 사용자가 단축키를 제작하는 명령어이다.
	5) 

	※ 명령어 정리 : http://kwonnam.pe.kr/wiki/git/cheatsheet