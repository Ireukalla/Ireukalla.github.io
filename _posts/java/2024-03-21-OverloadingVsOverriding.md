---
title: Overloading vs Overriding
date: 2024-05-04 12:00:00 +0000
categories: [Java]
tags: [Java]
author: Sahdaijin
mermaid: true
---

## Overloading
* 같은 클래스 내부에서 같은 메서드 이름을 가지고 있지만 **매개변수의 타입 or 개수 or 순서가 다른 메서드**
<!-- A method within the same class that has the same method name but differs in parameter type, number, or order -->

* 예를 들어 "add(int a, int b)", "add(double a, double b)" 두 개의 add 메서드는 이름이 동일하지만 매개변수 타입이 다르므로 오버라이딩이 가능하다.
<!-- For example, the two "add" methods, "add(int a, int b)" and "add(double a, double b)" have the same name but different parameter types, so they can be overridden. -->

* 어떤 메서드를 사용할지는 컴파일 단계에서 결정된다.
<!-- The determenation of which method to use is made at the compile time. -->

## Overriding
* 상위 클래스에서 이미 정의된 메서드를 하위 클래스에서 **동일한 시그니처(메서드 이름, 매개변수 타입 및 변수)로** 다시 정의하는 것
<!-- It is the redefinition of a method in a subclass that was already defined in the superclass with the same signature(method name, parameter types, and order) -->

* @Overriding 어노테이션은 필수가 아니지만 컴파일 단계에서 실제 오버라이딩 여부를 검사해 주므로 사용하는 것을 추천한다.
<!-- The "@Override" annotation is not mandatory, but it is recommended to use it because it helps to check the actual overriding during the compile time. -->

## 요약
* Overloading - 같은 클래스 내부에서 이름이 같은 메서드가 다른 시그니처를 가지고 있는 것
<!-- Overloading - methods within the same class having the same name but different signatures. -->

* Overriding - 상속관계의 하위 클래스가 상위 클래스의 이름과 시그니처가 같은 메서드를 재정의 하는 것
<!-- Overriding - When a subclass in an inheritance relationship redefines a method with the same name and signature as that in the superclass. -->