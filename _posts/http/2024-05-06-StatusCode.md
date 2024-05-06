---
title: Http Status Code
date: 2024-05-06 12:00:00 +0000
categories: [Web, Http]
tags: [Web, Http]
author: Sahdaijin
mermaid: true
---

## Http Status Code
### 주요 http response status code 정리

* __200 OK__ - 요청이 성공하여 리소스가 정상적으로 반환
* __201 CREATED__ - 요청이 성공하여 새로운 리소스가 생성
* __204 NO_CONTENT__ - 요청이 성공했지만 응답에 내용이 없음
---
* __400 BAD REQUEST__ - 요청이 잘못되어 서버가 핸들링 불가능
* __401 UNAUTHORIZED__ - 인증이 실패했거나 하지 않은 요청
* __403 FORBIDDEN__ - 요청이 서버에 의해 거부(권한 X)
* __404 NOT_FOUND__ - 요청한 리소스를 서버가 찾을 수 없음
---
* __500 INTERNAL_SERVER_ERROR__ - 서버 내부에서 오류가 발생하여 요청을 처리할 수 없음
* __503 SERVICE_UNAVAILABLE__ - 서버가 현재 사용할 수 없는 상태
* __504 GATEWAY_TIMEOUT__ - 응답시간이 초과된 상태