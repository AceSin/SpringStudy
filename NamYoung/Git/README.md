## Git 기본 명령어 정리

~~~
git init
	* 실행한 위치를 git 저장소로 초기화
	
git add [file name]
	* 해당 파일을 git이 추적할 수 있게 저장소에 추가
	
git commit
	* 변경된 파일을 저장소에 제출
	
git status
	* 현재 저장소의 상태 출력
	
git clone
	* 원격 저장소의 모든 내용을 로컬 저장소로 복사
	
git remote
	* 로컬 저장소를 특정 원격 저장소와 연결
	
git push
	* 로컬 저장소의 내용을 보내거나, 로컬 저장소의 변경 사항을 원격 저장소로 전송
	
git fetch
	* 로컬 저장소와 원격 저장소의 변경 사항이 다를 때 이를 비교 대조하고,
	  git merge 명령어와 함께 최신 데이터를 반영하거나 충돌 문제 등을 해결
	  
git pull
	* git remote 명령을 통해 서로 연결된 원격 저장소의 최신 내용을 로컬 저장소로 가져오면서 병합
 
git branch [name]
	* 'name'에 해당하는 이름의 브랜치 생성
	 
git checkout [branch name]
	* 현재 작업 중인 브랜치를 'branch name'으로 변경

git merge [branch name]
	* 현재 작업 중인 브랜치에 'branch name'의 브랜치를 끌어와 병합

git log -p
	* 각 커밋에 적용된 실제 변경 내용 확인

git log --word-diff
	* diff 명령의 실행 결과를 단어 단위로 확인

git log --stat
	* 각 커밋에서 수정된 파일의 통계 정보 확인

git log --name-only
	* 커밋 정보 중에서 수정된 파일의 목록 확인

git log --relative-date
	* 정확한 시간을 보여주는 것이 아니라 1일 전, 1주 전처럼 상대적인 시간을 비교하는 형식으로 확인

git log --graph
	* 브랜치 분기와 병합 내역을 아스키 그래프로 확인
~~~