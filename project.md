# com.dataagg:DAFramework:0.1
DAFramework

## com.dataagg:commons:0.1
公用实体类,VO及常用工具类

+ compile 'org.jodd:jodd-core:3.8.5'
+ compile 'org.jodd:jodd-bean:3.8.5'
+ compile 'org.jodd:jodd-props:3.8.5'
+ compile 'com.google.code.gson:gson:2.8.0'
+ compile 'org.nutz:nutz:1.r.61'
+ compile 'mysql:mysql-connector-java:6.0.6'
+ compile 'org.springframework.boot:spring-boot-starter-jdbc:1.5.3.RELEASE'
+ compile 'org.springframework.boot:spring-boot-starter-web:1.5.3.RELEASE'
+ compile 'org.springframework.boot:spring-boot-starter-security:1.5.3.RELEASE'
+ compile 'org.springframework.security:spring-security-core:4.2.2.RELEASE'
+ compile 'org.springframework.security.oauth:spring-security-oauth2:2.0.13.RELEASE'
+ testCompile 'junit:junit:4.12'
+ testCompile 'org.springframework.boot:spring-boot-starter-test:1.5.3.RELEASE'

## com.dataagg:api-gateway:0.1
api-gateway(API网关)+security(权限检查服务)

+ testCompile 'org.springframework.boot:spring-boot-starter-test'
+ compile 'org.springframework.boot:spring-boot-starter-web'
+ compile 'org.springframework.cloud:spring-cloud-starter-zuul'
+ compile 'org.springframework.cloud:spring-cloud-starter-feign'
+ commons
+ compile 'mysql:mysql-connector-java:6.0.6'
+ compile 'org.springframework.boot:spring-boot-starter-jdbc'

## com.dataagg:core-service:0.1
核心服务 用户,组织,角色,菜单,字典,区域,附件等基础服务

+ testCompile 'org.springframework.boot:spring-boot-starter-test'
+ compile 'org.springframework.cloud:spring-cloud-starter-feign'
+ commons
+ compile 'org.springframework.boot:spring-boot-starter-web'
+ compile 'mysql:mysql-connector-java:6.0.6'
+ compile 'org.springframework.boot:spring-boot-starter-jdbc'
+ compile 'org.springframework.boot:spring-boot-starter-security'
+ compile 'org.springframework.security.oauth:spring-security-oauth2'
+ compile 'org.springframework.cloud:spring-cloud-security:1.1.3.RELEASE'

# 项目依赖
```graphLR
commons[commons]
api-gateway[api-gateway]
api-gateway-->commons[commons]
core-service[core-service]
core-service-->commons[commons]
```
