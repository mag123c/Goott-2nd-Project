# ★ 2차 프로젝트 화이팅 ★

# 주의사항
1. 타 팀원과 겹치는 작업페이지 내부에서는 각자 성함과 어느파트인지 주석으로 철저히 구역 구분 해주세요
2. 각 컴퓨터 환경 바뀌실때마다 UTF-8 꼭 확인 부탁드립니다
3. 본인 작업 메소드 상단에 메소드 작업내용(간략하게), 시작일자, 성함 주석으로 입력해주세요 ( 노션 > 회의록 > 230206 회의록 파일 참조요청 )
4. 꼭!! Pull requests 할때는 develop branch 로 요청 부탁드립니다

############################

230207 Git Hub Start

230209 1차 전체병합 진행 > 완료
> user section : login, qna 완료
  
230210 2차 전체병합 진행 > 완료
> 카카오, 네이버 로그인 버튼 클릭 시 가입상태이면 video/list, 아니면 signin화면
> 
> 아이디, 비밀번호, 비밀번호 확인 , 닉네임, 휴대폰 번호 유효성 검사, 로그인 페이지 작업 완료
> 
> pom.xml 에 메일 관련 dependency 추가
> 
> root-context에 메일관련 빈 추가
> 
> video/list 카테고리별로 분류해서 가져오는기능 , 이미지 캐러셀기능
  
230215 3차 전체병합 진행 > 완료
> 비밀번호 찾기, 아이디 중복확인, 회원가입시 이메일 인증, 닉네임 빈칸&특수문자 유효성 검사, 비밀번호 확인 작업 완료
> 
> CRUD 게시판&페이징 처리, KAKAO 결제 및 결제기간 입력 시 자동업데이트 완료
> 
> video list 내 영화 장르별로 분류기능, video detail 영상정보&배우정보 가져오기 

230217 4차 전체병합 진행 > 완료
> 회원가입 페이지 내 '인증번호 color, 비밀번호 확인 아이콘' 오류사항 해결 완료

> 관리자 페이지 카테고리, 장르별 차트 작업 완료 > 연결X 페이지 작업만 완료 상황

> 내 비디오 보관함 페이지 기능 및 작업 90% 완료

230220 5차 전체병합 진행 > 완료
> QNA 비밀 글 기능, 수정, 답변 수정, 답변 등록, 보기, URL접근 시 차단 등 완료

> 관리자 페이지 View셋팅, 차트, 일 방문자, 전체방문자, 매출현황, 관리자 DB접근 재설계, 관리자가 DB 접근이 가능하게 하기 위해 CRUD 테이블 생성 / IDEO에 함축해서 올리면 테이블별로 뿌려서 DB셋팅되게 할 예정

> video list 검색기능 추가 > list.jsp에서만 적용되기때문에 1차 종료 후 차후 navbar관련하여 공용여부 회의 후 변경가능성 있음

> 내 정보 페이지 내 유저정보 가져오기, 수정 및 DB저장 완료

> mypage 보관함 list구현, main.jsp 주소 변경 및 회원조회 삭제(관리자 페이지로 이동시킬 예정), userController에서 주소변경, 시작화면 프로토타입 수정 후 붙여넣음 -> main컨트롤러 에서 주소수정

230224 6차 전체병합 진행 > 완료
> 마이페이지 내 정보수정 : 수정할 수 있는 모달창 띄우기 완료, 이메일 입력칸 이메일형식 검수 / 기존 이메일과 동일시 이메일인증 버튼 비활성화 처리 / 닉네임 입력창 공란,특수문자 입력방지 / 휴대폰번호 숫자만 허용 및 13자리 미입력시 수정버튼 비활성화 / 회원가입 에러사항 해결완료

> video list 페이지 내 영상 검색기능 완료 > 차후 타 페이지들에 대한 navbar 회의 진행 필요

> video list 내 main video 새로고침 할때마다 랜덤한 영상 재생되도록 수정 완료

> 관리자 페이지 차트 2개 추가, DB, 영상 추천수 별 정렬작업 완료 / QnA 알림기능 끝(근데 안멈춤, 수정필요)

> 기본 주소 (localhost:8081) 메인페이지와 연결 완료 / 내 보관함 기능 완료

230227 7차 전체병합 진행 > 완료
> 관리자 채팅 및 잡동사니 수정 완료 / 최종취합 후 최종test 예정

> 원댓글 수정, 삭제 / 대댓글 불러오기 완료

> navbar분할작업 / 회원가입성공 alert출력후 common/start 페이지로 이동하도록 수정 / 네비바 & 푸터 각 페이지마다 필요한 링크 삽입

> video list : 영문페이지 작업진행, view단에서는 작업 이전, list내에 top5 영상작업 진행 완료

230306 8차 전체병합 진행 > 완료
> video list로 main페이지 설정하여 로그인 후 video list로 이동완료

> 사용자 이미지 설정 및 view 기능 완료

> video detail 댓글, 대댓글 CRUD 
