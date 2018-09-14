# 更改 application.yml 账号，密码
spring:
    datasource:
        type: com.alibaba.druid.pool.DruidDataSource
        driverClassName: com.mysql.jdbc.Driver
        url: jdbc:mysql://localhost:3306/fsupa?useUnicode=true&characterEncoding=UTF-8
        username: 账号
        password: 密码

运行localhost:8082/即可启动