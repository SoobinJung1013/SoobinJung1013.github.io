---
layout: post
title:  "시스템 아키텍쳐 🌟"
author: "Soobin Jung"
comments: true
tags: Tale


---

![System Architecture](https://SoobinJung1013.github.io/images/architecture.png)

-  [What is Nginx](https://www.nginx.com/resources/glossary/nginx/)

  ​	: NGINX is open source software for web serving, [reverse proxying](https://ko.wikipedia.org/wiki/리버스_프록시), 	caching, load balancing, media streaming, and more. It started out as 	a web server capabilities, NGINX can also function as a proxy server 	for email. (IMAP, POP3, and SMTP) and a reverse proxy and load balancer for HTTP, TCP, and UDP servers.

  - ​	[nginx 위키백과](https://ko.wikipedia.org/wiki/Nginx)

  - [what is web server?](https://soobinjung1013.github.io/2021-02-06/basic)

    : Nginx 는 요청에 응답하기 위해 [비동기](https://www.yalco.kr/21_async/) [이벤트](https://ko.wikipedia.org/wiki/이벤트_(컴퓨팅)) 기반 구조를 가진다. 이것은 [아파치 HTTP 서버](https://namu.wiki/w/아파치%20HTTP%20서버)의 [스레드/프로세스](https://gmlwjd9405.github.io/2018/09/14/process-vs-thread.html) 기반 구조를 가지는 것과는 대조적이다. 이러한 구조는 서버에 많은 부하가 생길 경우의 성능을 예측하기 쉽게 해준다. 

- [About React](https://ko.reactjs.org)

  : React는 사용자 인터페이스를 구축하기 위한 선언적이고 효율적이며 유연한 JavaScript 라이브러리이다. "컴포넌트"라고 불리는 작고 고립된 코드의 파편을 이용하여 복잡한 UI를 구성하도록 돕는다.

  [리액트 자습서](https://ko.reactjs.org/tutorial/tutorial.html#before-we-start-the-tutorial)

- [정적인 페이지 vs 동적인 페이지](https://titus94.tistory.com/4)

- [What is gunicorn ?](https://this-programmer.tistory.com/entry/gunicorn은-대체-뭐하는-놈일까-부제-CGI-WSGI는-대체-뭐냐)

  - CGI (Common Gate Interface) : 웹 서버와 응용프로그램 사이의 동시통역사

  - WSGI (Web Server Gateway Interface)

  - 미들웨어

    >
    >
    >그러니까 Gunicorn이나 uWSGI는 Apache나 nginx로 들어오는 HttpRequest를 Python이 이해할 수 있게 동시통역하여 던져주는 애들이라고 할 수 있는 것이다. 글을 들어가면서 말했던, 이러한 미들웨어가 필요없어보이는 php도 apache서버를 설정할 때 주석 해제를 통해 php버전에 맞게 모듈을 활성화시키는 걸 알고 있을 것이다. 그것이 바로 CGI역할을 하는 것이다. 스프링을 배포할 때에는 톰캣이 이러한 역할을 맡는다고 보면 쉽게 이해가 될 것이다. 그리고 이렇게 해석기와 웹서버가 달려있는 애들을 흔히 WAS(Wep Application Server)라고 부른다.

  --> 이 부분 [요런식](https://khanrc.tistory.com/entry/WSGI로-보는-웹-서버의-개념)으로 정리 ㄱ ㄱ

- what is docker?

