---
layout: post
title:  "LAMBDA?"
date:   2022-12-28 19:41:57 +0900
categories: [Java , Basic]
tags: [java, lambda]
---

# What is Lambda?
---

메서드를 하나의 `식`으로 표현한 것
```java
//평문
int max(int a, int b){
    return a>b ? a : b;
}
//람다 (타입이 추론 가능할때 생략가능)
(a,b) -> { return a > b ? a : b;} //리턴일때는 중괄호 생략 불가

그밖에
(int a) -> a*a; = a-> a*a; //매게변수 괄호 생략가능
(String name, int i) -> System.out.println(name+"="+i) //중괄호 생략가능

```