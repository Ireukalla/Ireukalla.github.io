---
title: Overloading vs Overriding
date: 2024-05-04 12:00:00 +0000
categories: [Java]
tags: [Java]
author: Sahdaijin
mermaid: true
---

## Overloading
* 같은 클래스 내부에서 같은 메서드 이름을 가지고 있지만 매개변수의 타입, 개수, 순서가 다른 메서드, 컴파일 단계에서 어떤 메서드가 호출 될지 결정된다.
* 예를 들어 "add(int a, int b)", "add(double a, double b)" 두 개의 add 메서드는 이름이 동일하지만 매개변수 타입이 다르므로 오버라이딩이 가능하다.

## Overriding
* 상위 클래스에서 이미 정의된 메서드를 하위 클래스에서 동일한 시그니처(메서드 이름, 매개변수 타입 및 변수)로 다시 정의하는 것
* @Overriding 어노테이션은 필수가 아니지만 컴파일 단계에서 실제 오버라이딩 여부를 검사해주므로 사용하는 것을 추천한다.

## 요약
* Overloading - 같은 클래스 내부에서 이름이 같은 메서드가 다른 시그니처를 가지고 있는 것
* Overriding - 상속관계의 하위 클래스가 상위 클래스의 이름, 시그나처가 같은 메서드를 재정의 하는 것