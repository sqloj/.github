# SQLOJ

SQLOJ 是一个SQL语句在线评判系统。

## 简介

前端的技术选型是 [Vue](https://staging-cn.vuejs.org/) 和 [TypeScript](https://www.typescriptlang.org/)，使用的组件库是 [Naive UI](https://www.naiveui.com/zh-CN/)。

后端的技术选型 [Spring Boot](https://spring.io/projects/spring-boot) 和 [MyBatis](https://mybatis.org/mybatis-3/zh/index.html)，数据库选择 [MariaDB](https://mariadb.org/)。

评测端目前支持两种，MariaDB 和 H2 数据库。未来可能支持更多。

![image](https://user-images.githubusercontent.com/42564206/169650424-bb2c8d11-fed6-442d-a271-f808f1ef97fc.png)


## 部署

部署使用 [Docker](https://www.docker.com/)，配置环境更简单，部署起来更方便。

请确认已安装 Docker 和 Docker Compose。然后执行

```shell
$ git clone https://github.com/sqloj/sqloj-docker.git
$ cd sqloj-docker/compose/test
$ docker-compose up -d
```

稍等片刻，即可在 http://localhost:10085 访问。

更多部署配置，请访问 https://github.com/sqloj/sqloj-docker 。
