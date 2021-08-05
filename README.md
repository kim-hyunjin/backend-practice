## 클래스101 백엔드 실무

### 참고자료 목록

- 스트레스 테스스 툴 : Artillery
  - https://artillery.io/docs/guides/overview/welcome.html

- 도커
  - https://subicura.com/2017/02/10/docker-guide-for-beginners-create-image-and-deploy.html
  - https://subicura.com/2017/01/19/docker-guide-for-beginners-1.html

- 젠킨스
  - https://gist.github.com/lleellee0/6c8fa84c5055c16125f00222cabc4d17

- nginx
  - https://gist.github.com/lleellee0/8e1be478178078e931dd3180f0f56d21
  - https://docs.nginx.com/nginx/admin-guide/load-balancer/http-load-balancer/
- RabbitMQ
  - https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-amqp/2.4.1
  ```
  # RabbitMQ를 도커로 실행시키기 위한 명령어
  docker run -d --hostname my-rabbit --name some-rabbit -p 5672:5672 -p 15672:15672 rabbitmq:3-management
  ```
  
