## 커뮤니티 사이트 만들기


회원가입 폼   
GET http://yejin.com/usr/member/join  
  
회원가입  
POST http://yejin.com/usr/member/join  
DATA  
username=admin  
password=admin1234  
name=Paul  
email=test@test.com  
  
로그인 폼   
GET http://yejin.com/usr/member/login  

로그인  
POST http://yejin.com/usr/member/login  
DATA  
username=admin  
password=admin1234  
  
로그아웃  
POST http://yejin.com/usr/member/logout  
  
자유 게시물 리스트  
GET http://yejin.com/usr/article/list/free  
  
자유 게시물 삭제  
POST http://yejin.com/usr/article/delete/free/1  
  
자유 게시물 상세내용  
GET http://yejin.com/usr/article/detail/free/1  
  
자유 게시물 작성폼  
GET http://yejin.com/usr/article/write/free  
  
자유 게시물 작성  
POST http://yejin.com/usr/article/write/free  
DATA  
title=제목    
body=내용  
  
자유 게시물 수정폼  
GET http://yejin.com/usr/article/modify/free/1  
  
자유 게시물 수정  
POST http://yejin.com/usr/article/modify/free/1  
DATA  
title=제목  
body=내용  
