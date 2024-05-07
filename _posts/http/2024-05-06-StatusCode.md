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

* **200 OK** - 요청이 성공하여 리소스가 정상적으로 반환
* **201 CREATED** - 요청이 성공하여 새로운 리소스가 생성
* **204 NO_CONTENT** - 요청이 성공했지만 응답에 내용이 없음

---

* **400 BAD REQUEST** - 요청이 잘못되어 서버가 핸들링 불가능
* **401 UNAUTHORIZED** - 인증이 실패했거나 하지 않은 요청
* **403 FORBIDDEN** - 요청이 서버에 의해 거부(권한 X)
* **404 NOT_FOUND** - 요청한 리소스를 서버가 찾을 수 없음

---

* **500 INTERNAL_SERVER_ERROR** - 서버 내부에서 오류가 발생하여 요청을 처리할 수 없음
* **503 SERVICE_UNAVAILABLE** - 서버가 현재 사용할 수 없는 상태
* **504 GATEWAY_TIMEOUT** - 응답시간이 초과된 상태