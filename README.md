## team project 2 <앱 기획 및 구축>

__팀 프로젝트 23/12/01 ~ 23/12/22__

__12/01__
개발할 어플에 대한 다양한 아이디어 모음
피드백을 통해 가장 적절한 아이디어를 선정
팀 내 역할을 분담
팀명을 정한 후 추후 진행 과정을 정리
각자 사용자 시나리오를 작성한 후 공유

__12/02__ 
각자 작성한 사용자 시나리오를 바탕으로 최종 사용자 시나리오를 작성
워크플로우와 유스케이스에 대한 의견을 나눈 후 작성

__12/03__ 
유스케이스와 워크플로우를 좀 더 다듬어 완성하였고, 요구사항 분석을 작업
기본적으로 작성된 요구사항 분석에서 각 조원의 피드백을 모아 최종 요구사항 분석 문서를 완성

__12/04__ 
주말동안 작업한 문서(워크프레임, 유스케이스)들에 대한 피드백을 받고 수정 작업
요구사항 분석에서 많은 수정이 필요하여 기능적 요구사항과 비기능적 요구사항으로 분류하여 작업하였고, 
조원들이 함께 의견을 내어 수정해가며 완성
간단한 UI 프로토타입을 각자 작업하여 공유한 후 피드백을 주고 받음

__12/05__
기능적/디자인적 레퍼런스 어플을 찾은 후 피드백을 받아 최종으로 참고할 어플을 선정
이전 작업했던 워크플로우, 프로토타입 구성을 기반으로 기능적인 부분에 대한 회의 후 요구사항 최종 수정
프로토타입 구성을 기반으로 디렉토리 구조에 대해 의논하고 작성

__12/06__ 
레이아웃적인 부분을 회의를 통해 세세하게 수정하며 작업 
디렉토리 구조에 대한 자세한 피드백을 듣고 피드백을 기반으로 수정을 진행
프로토타입과 디렉토리 구조를 기반으로 파일과 폴더를 생성하고 정리해 나가며 작업 방향을 잡으려고 해봤지만 쉽지 않았음.

__12/07__ 
작업에 들어갈 준비 시작
스타일 작업을 위한 가이드라인을 상의하여 정리
회의를 통해 메인 컬러와 폰트를 선정하여 정리
작업을 시작하기에 앞서 간단한 코딩 가이드를 상의하에 정리
수정한 디렉토리 구조를 기반으로 디렉토리를 쌓고 ‘shopping’ 페이지의 레이아웃을 완성
디자인에 필요한 일러스트 작업

__12/08__ 
푸드 리스트 영역 일부 구현
구현 중 추가 컴포넌트가 발생해 디렉토리 구조를 일부 수정하고 냉장고 등록 영역의 기능을 수정

__12/11__ 
디자인 작업 - 채색된 일러스트와 선정한 테마컬러가 어울리지 않아 컬러를 전체적으로 수정 
포인트 컬러 결정
기능 작업 - 푸드리스트에 대한 수정/삭제 기능을 계속해서 고민하고 구현함.
수정까지는 수월하게 진행되었는데 수정페이지에서 삭제 버튼을 누르면 랜덤으로 데이터가 삭제되는 현상이 발생 
→ 수정하고 있는 데이터를 대상으로 삭제가 이루어지도록 코드를 수정하여 해결
식품의 날짜 입력 시 날짜 형태(YYYY-MM-DD)의 형태로 나타나게 하고 캘린더 위젯을 활용할 수 있도록 연결

__12/12__ 
디자인에 대한 피드백을 받은 후 피드백을 기반으로 불필요한 기능적 요소 제거하고, 전체적으로 통일감 있고 더 눈에 띄는 UI로 디자인 수정
그림 일러스트가 통일감이 떨어진다 생각하여 아이콘을 이용한 디자인으로 모두 변경
식료품 데이터 추가 시에 데이터 값이 리스트에 뜨지 않는 문제를 해결하려 여러 가지 방법을 사용해봤지만 해결하지 못함

__12/13__ 
식료품을 추가한 후 추가된 데이터 값을 리스트에 바로 보이게 구현 성공
최상위 컴포넌트에서 데이터 값을 선언하고 관리하도록 하여 자식 컴포넌트들에게 데이터를 더 쉽게 나누고 나타나게 함
이후 수정 기능의 컴포넌트를 분류하여 수정페이지를 따로 관리하려 했지만 해결하지 못함
완료된 디자인과 기능 페이지를 우선적으로 하여 css 작업 진행

__12/14__ 
각자 만든 페이지를 합쳐 동작하는 기능을 확인하였고, 그에 따른 css 작업 진행
저장된 식료품 수정 기능은 컴포넌트를 분리하는 대신 같은 컴포넌트 안에서 모달창을 띄우는 방식으로 하여 부분적으로 해결
다만 수정을 하고 나서 새로고침을 해야 리스트가 업데이트 되는 점, 수정 시 원래의 값이 모두 뜨지 않는 문제점들이 생김

__12/15__ 
중간 피드백 받음
계정 로그아웃을 위한 설정 페이지 추가
식품 정렬, 검색기능 코드작성 
이미지 소스를 전체적으로 통일감 있게 수정하고 푸드아이템의 디데이 기능을 구현
전체적인 css 작업을 실행하고 수정

__12/18__
식료품 리스트 삭제버튼을 수정모달창 안으로 위치 변경, 
변경후 생긴 카테고리 분류 후 삭제 시 다른 리스트가 삭제되는 오류 해결  
캘린더 기능을 “full-calendar” 플러그인을 사용하여 구현
원하는 데이터를 캘린더에 이벤트로 나타나게 한 후 css 작업을 통해 스타일을 구현
모든 컴포넌트들을 합친 후 기능적으로 오류가 없는지 확인하고 문제가 발생하는 부분을 수정
어플 로고 디자인과 시작화면 디자인을 계속해서 고민

__12/19__ 
splash 페이지 디자인 변경
전체적인 css 스타일 작업 마무리
모든 컴포넌트들을 합친 후 좀 더 통일감 있게 디테일을 수정
완료된 작업을 기반으로 워크플로우와 프로토타입, 디렉토리 구조를 수정
발표를 위한 내용을 정리

__12/20__ 
발표를 위한 ppt자료를 준비
팀원 간 의견 교환으로 ppt의 전체적인 흐름과 내용의 틀을 짠 후 자료를 준비하고 대본을 준비한 후 서로의 피드백을 통해 완성

__12/21__ 발표 준비를 마친 후 발표를 진행
발표 후 선생님의 피드백을 듣고 그에 따라 ppt자료와 프로젝트 작업들을 수정