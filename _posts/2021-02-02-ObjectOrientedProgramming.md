---
layout: post
title:  "Object Oriented Programming"
author: "Soobin Jung"
comments: true
tags: Tale

---

자바스크립트는 객체 기반의 프로그래밍 언어로, 자바스크립트를 이루고 있는 거의 "모든 것"이 객체다. 

원시 타입의 값을 제외한 나머지 값들(함수, 배열, 정규 표현식 등)은 모두 객체다. 



객체 지향 프로그래밍은 실세계의 실체 (사물이나 개념)를 인식하는 철학적 사고를 프로그래밍에 접목하려는 시도에서 시작한다. 실체는 특징이나 성질을 나타내는 _속성_을 가지고 있고, 이를 통해 실체를 인식하거나 구별할 수 있다.

**객체지향 프로그래밍**	

```javascript
const circle = {
	radius: 5, // 반지름
	
	getDiameter() {
		return 2 * this.radius;
	},
	
	getPerimeter() {
		return 2 * Math.PI * this.radius;
	},
	
	getArea() {
		return Math.PI * this.radius ** 2;
	}
};

console.log(circle);
// {raduis: 5, getDiameter: f. getPerimeter: f, getArea: f}

console.log(circle.getDiameter()); //10
```

객체의 상채를 나타내는 _상태데이터_  : 반지름 

상태데이터를 조작할 수 있는 _동작_  : 원의 지름, 둘레, 넓이를 구하는 것

객체 : _상태 데이터와 동작을 하나의 논리적인 단위로 묶은 복합적인 자료구조_. 즉, 속성을 통해 여러 개의 값을 하나의 단위로 구성한 복합적인 자료구조이다.

이때 객체의 상태 데이터를 프로퍼티, 동작을 메서드라고 부른다. 



각 객체는 고유의 기능을 갖는 독립적인 부품으로 볼 수 있지만 자신의 고유한 기능을 수행하면서 다른 객체와 관계성을 가질 수 있다. 다른 객테와 메시지를 주고받거나 데이터를 처리할 수도 있다. 또는 다른 객체의 상태 데이터나 동작을 상속받아 사용하기도 한다.

