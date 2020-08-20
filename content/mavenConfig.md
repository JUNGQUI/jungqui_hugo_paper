---
title: "MavenConfig"
date: 2020-08-20T17:51:15+09:00
draft: true
---

maven repository 적용

각 버전에서 그에 맞는 dependency version 과 dependency module 을 붙여줘야 한다.

ex) springframework-core : common-logging 1.2 가 필수
따라서 common-logging 1.2 를 dependency 로 붙여주고 이후에 spring-core 를 붙여야 정상적으로 build 가 된다.