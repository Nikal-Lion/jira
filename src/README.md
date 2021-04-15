# Jira software install in docker

## MySQL

- 用 MySQL 作为存储数据库
- 字符集设置为utf8mb4 排序规则为utf8mb4_bin （jira运行要求）

## Jira 目录详解

- atlassian-extras-3.2.jar 是破解jira的jar包
- mysql-connector-java-5.1.25-bin.jar 是mysql的JDBC连接工具
- atlassian-universal-plugin-manager-plugin-2.22.4.jar 未使用本jar包

## Jira

- 镜像： [dchevell/jira-software:7.13.6](https://hub.docker.com/r/dchevell/jira-software)
- 该镜像包含agile