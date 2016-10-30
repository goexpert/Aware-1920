# Aware-1920
##1. 주제
폭이 1920px인 그리드 디자인 쇼핑몰
<br><br>
##2. 프로젝트 목적
이번 과제는 완성을 목적으로 하기 보다 팀 빌딩 이후 Github, Slack, Trello와 같은 협업 도구들을 연동하고 팀내 가이드를 만들어가는 과정에 초점을 두고 진행.
<br><br>
##3. 도전해볼만한 것
	- 가이드라인 작성
	- 병행작업
	- 이슈 사용 및 코드 리뷰
	- 워크플로우를 적용한 협업
##4. 협업 포인트
###4.1 처음 계획한 과제 협업 포인트

	- 모듈로 만들 대상
	- 가이드라인을 참고하여 코드리뷰
	- 읽기 쉬운 코드 작성 습관
가이드 작성 및 협업 과정에 문제를 발견하는데 초점을 두고 진행.
*깃허브 작업환경 및 워크플로우 설정이 늦어져서 과제 수행에서 얻고자 하는 부분을 수정함.*
###4.2 수정된 과제 협업 포인트
	- 팀에서 정한 워크플로우에 맞춰서 깃허브 활용
	- 작업을 진행하면서 가이드 후보 찾기
##5. 팀 도구 - 별도 정리
<br>
##6. 작업 방법
	- 전체 분석/설계하지 말고 공통부분을 우선 작업하고 작은 업무단위로 분리해서 진행
	- 공통 css는 모듈화해가며 지속적으로 업데이트 및 기존 작업 내용에 적용
	- 작업 영역을 나누고 작업 내용을 선택해서 작업별 커밋해서 채워나가는 방향으로 진행(깃허브 이슈 활용)
	- 스타일 리셋을 제외한 코드는 되도록 다른 요소에 영향을 주지 않도록 해야함
##7. 작업순서
	1. 그리드
	2. 영역 선택 및 작업 진행
	3. 작업 내용 리뷰
	4. 작업 내용 반영
##8. 기타
	- CSS, HTML, Javascript, Github-Workflow는 별도의 저장소에 관리
	- 가이드는 선택하여 적용할 수 있도록 고려되어야 함.(예 : 깃 워크플로우, 코드 컨벤션)
	- 리셋을 바로 적용하지 말고 normalize 만 적용한 후에 기본 요소의 속성이 리셋이 필요한 경우 의논하여 공통 css에 리셋 적용
	
---
#팀 프로젝트 가이드 회의 내용 (10.27) 


##1.공통 
- center 지정하는 부분 믹스인으로 설정 
- 들여쓰기 규칙 : 소프트 탭으로 2칸 (탭을 누르면 스페이스가 적용 )


##2.HTML
- HTML요소내 속성 표기 순서 
   - 이름에 대한 규칙에 대해서는 다른 레퍼런스들을 찾아보도록 (  ex. airbnb )
- id지정은 나중에 바꾸도록 , 스크립트 채우기 전에는 더미id라도 사용한다 (form에서만) 



##3.CSS
- 속성 순서 : 위치 - 박스모델 - 꾸미기


##4.SASS
- map 파일은 만들자
