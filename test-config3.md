spring:
  profiles:
    active: test

---
server:
  port: 11111
spring:
  profiles: dev
  application:
    name: test-config3

---
server:
  port: 22222
spring:
  profiles: test
  application:
    name: test-config3

---
server:
  port: 33333
spring:
  profiles: prod
  application:
    name: test-config3