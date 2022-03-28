# elice-webProject
###엘리스 포트폴리오 사이트 프로젝트 좋아요, 수상 기록 백엔드

##awardRouter

Awardrouter.post("/award/create")
수상기록 저장

Awardrouter.get("/awardlist/:userId/:sortKey?")
수상리스트 가져오기

Awardrouter.put("/awards/:id")
수상기록 수정

Awardrouter.get("/awards/:id")
수정한 수상기록 새로 가져오기

Awardrouter.delete("/awards/:id")
수상기록 삭제

##Likerouter
ikerouter.post("/like/add")
좋아요 저장
좋아요 기록이 있으면 삭제 없으면 저장

Likerouter.get("/likecount/:userId")
좋아요 누른 사람 수 가져오기

## common utils.js
권한 설정
