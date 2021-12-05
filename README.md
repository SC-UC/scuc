# 소개
스타 대학별 랭킹을 제공하는 웹 사이트

# 기술 스택
* Spring Boot
* Apache Tomcat

# 서비스 아키텍처
[ 도표 추가 ]

* reverse proxy: nginx
* frontend: [WAS](https://github.com/SC-UC/scuc)
* backend: [api](https://github.com/SC-UC/scuc-api), db, [crawler](https://github.com/SC-UC/scuc-crawler)

# API 명세
## api server
|method|URI|description|
|---|---|---|
|GET|/sample|샘플|

