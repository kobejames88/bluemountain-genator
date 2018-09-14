# 更改 application.yml 账号，密码
<br>
spring:
<br>
    datasource:
    <br>
        type: com.alibaba.druid.pool.DruidDataSource
        <br>
        driverClassName: com.mysql.jdbc.Driver
        <br>
        url: jdbc:mysql://localhost:3306/fsupa?useUnicode=true&characterEncoding=UTF-8
        <br>
        username: 账号
        <br>
        password: 密码
<br>
运行localhost:8082/即可启动