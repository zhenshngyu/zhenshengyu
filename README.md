﻿spring:
  profiles:
    active:
      - dev
---
spring:
  profiles: dev   #开发环境
  application:
    name: greecloud-config-bdqn-dev
---
spring:
  profiles: test  #测试环境
  application:  
    name: greecloud-config-bdqn-test
#   请保存为UTF-8格式
