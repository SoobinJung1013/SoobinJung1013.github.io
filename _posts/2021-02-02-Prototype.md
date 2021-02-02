---
layout: post
title:  "Prototype"
author: "Soobin Jung"
comments: true
tags: Tale

---

Prototype

===

자바스크립트는 객체 기반의 프로그래밍 언어로, 자바스크립트를 이루고 있는 거의 "모든 것"이 객체다. 

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

객체 : _상태 데이터와 동작을 하나의 논리적인 단위로 묶은 복합적인 자료구조_

이때 객체의 상태 데이터를 프로퍼티, 동작을 메서드라고 부른다. 



**상속과 프로토타입**

