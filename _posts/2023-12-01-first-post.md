---
title : "github.io 블로그 시작해보기!"
excerpt : "Github Blog 서비스인 github.io 블로그를 시작하기로 했다!"

categories:
    - Blog
tags:
    - github blog
last_modified_at : 2023-12-01T08:06:00-05:00
---

Github Blog 서비스인 github.io 블로그를 시작하기로 했다.
Github Blog 서비스의 이름은 Pages이다.

Pages는 다른 블로그 플랫폼보다 편한 것 같아서 마음에 든다.

YFM에서 정의한 제목을 이중 괄호 구문으로 본문에 추가할 수 있다.
이 글의 제목은 {{ page.title }}이고
마지막으로 수정된 시간은 {{ page.last_modified_at}} 이다.

이때, YFM(YAML Front Matter ) 포멧에 대해 간단히 설명해본다.
YFM은 markdown 파일의 최상단에 위치하며 3개의 하이픈으로 시작과 끝을 표시한다.
YAML은 오픈 소스 프로젝트에서 많이 사용하는 구조화된 데이터 형식이다. 
YFM은 YAML을 사용해서 글의 제목, 날짜, 카테고리, 태그, 레이아웃 등을 정의할 수 있다.
YFM에서 정의한 제목인 title을 이중 괄호 구문으로 본문에 추가할 수 있다.