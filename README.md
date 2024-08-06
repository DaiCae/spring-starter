# Spring starter for Java 8

Require:

- JDK >= 17
- NodeJs >= 16

## Clone repository

[start.spring.io] depends on [initializr]

### initializr

> Before commit: Remove outdated Java 8 override

- git clone https://github.com/spring-io/initializr
- git checkout 1a676d7162a91e0e44c010b20a2deef4d01d6d0d

### start.spring.io

> Before commit: Remove support for Java 8 and 11

- git clone https://github.com/spring-io/start.spring.io
- git checkout 34a0ab691ca6efdb3695489a1e9ce59cd61c6807

### Maven package

- start-site.jar
- start-site-exec.jar

## CMD usage

java -jar start-site-exec.jar

## Docker usage

`cd docker && docker compose up -d`
