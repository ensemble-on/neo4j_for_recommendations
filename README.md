# neo4j_for_recommendations"

## Overview

이 코드는 Docker-compose 사용하여 추천 시스템에 사용될 백엔드 인프라를 구성하고자 한다. 

## Instructions

1. 아래 사이트를 참조하여 docker 를 설치한다. 여기서는 Windows 10 를 사용하였다.

   https://docs.docker.com/docker-for-windows/install/#download-docker-for-windows

2. 필요 시, docker-compose.yml 를 수정한다.

3. docker-compose.yml 파일이 위치한 디렉토리에서 아래 명령을 사용하여, 서비스를 시작한다.

   # 서비스 시작
   $ docker-compose up -d  

   # 서비스 중지
   $ docker-compose down

4. pgadmin4 console를 웹브라우저로 접근하여, postgres 와 연결한다. 이 때, connection 생성이 필요하다.

   http://localhost:5050

5. neo4j console 를 웹브라우저로 접근할 수 있다.

   http://localhost:7474