laravel project

- 현재 php 7.2 issue로 인하여 count() 충돌이 일어나는 것으로 보임.  7.1 버전으로 사용 시 에러가 없다고 함.

- 구현된 기능

사용자 인증 
 - 자체 인증 
 - 소셜 인증

기본 게시판
 - 글 (CRUD, 인증/인가된 사용자에게만 CUD 허용, 파일 또는 이미지 첨부, 태그부여,)
 - 태그 (태그별 글 목록)
 - 파일 첨부 (비동기 업로드, 이미지파일이면 본문에 삽입)
 - 댓글 및 투표
   (CRUD, 인증/인가된 사용자에게만 CUD 허용 , 계층 구조, 투표(좋아요,싫어요))


나머지 기능은 git으로 제공 해 준 코드를 사용함
 - 이메일 알림(댓글이 달리면)
 - 이메일 알림 사전동의
 - 목록 정렬
 - 전체 텍스트 검색
 - 이메일 알림
 - 다국어 지원
 - 모델쿼리에 캐싱 적용
