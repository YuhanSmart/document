#Git 정리
## Git 기본 명령어
	1) git config --global --list : 현재 설정정보 조회
	2) git config --global user.name "사용자명" : 이름 설정(필수)
	3) git config --global user.email "email" : 이메일 설정(필수)
	4) git config --global color.ui “auto” : 표시 메세지 컬러로 설정
	5) git status : 상태 조회
	6) git add <file> : 변경/수정 후 스테이징영역으로 올려준다.
	7) git commit -m '메세지' : 스테이징 영역에 있는 파일을 커밋하며 메세지를 남겨 변경이유를 기록한다.
	8) git push : 원격저장소에 파일을 올린다. 변경사항을 로컬저장소에 있는 파일과 합친다.
	9) git pull : 원격저장소에서 파일을 가져온다. 변경사항을 로컬저장소에 있는 파일과 합친다.
