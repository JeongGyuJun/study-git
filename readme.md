# Hello Git World

## git의 주요 개념
- 작업 디렉토리 (Working Directory) : cmd, bash, 소스트리 등에서 파일 분산 관리 작업을 눈으로 확인이 가능한 곳. 
- 준비 영역 (Staging Area, Stage/Index) : 로컬 저장소에 올라가기 전에 임시로 .git안에 저장되는 곳.
- 로컬 저장소 (Local Repository) : 로컬 저장소에 올라가서 자신이 수정한 파일을 업로드 받는 곳.
- 원격 저장소 (Remote Repository) :  Github 저장소에서 다같이 확인이 가능한 곳

## 기본 명령어
- git init : git으로 분산관리시스템을 작업을 가능하게 초기화 시켜줌.
- git status : git 작업이 부여되면 그 디렉터리 상황을 알 수 있음.
- git add : add명령어를 함으로써 작업 디렉토리 영역에서 준비영역으로 이동시킬 수 있음.
- git commit : git의 변경된 내용을 메세지로 남겨서 확인 할 수 있게 만듬.
- git log :  commit된 내용을 log 명령어로 확인 할 수 있음.
- git reset --hard : 로컬 저장소에 있었던 내용을 다시 작업 디렉토리로 가져옴.
- git rm --cached : 준비영역에 올라가 있던 것들도 rm -cached으로 내릴 수 있다.
