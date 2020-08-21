---
title: "github.io 블로그 시작"
excert: "3년전 만들어놓은 계정을 이제서야 제대로 사용해 보려한다"

categories:
  - blog
tags:
  - [github, pages]
last_modified_at: 2020-08-20T10:32:00-0700
---

아주 오랫동안 방치해두었던 GitHub 서비스인 github.io 블로그를 시작하기로 했다.
GitHub 서비스의 이름은 Pages이고 HTML과 MD 포맷을 사용할수있다.

예전 잠깐 사용해본 Javascript template처럼 YFM에서 정의한 것들은 이중 괄호 구문으로 본문에 추가할 수 있다.
예를 들어서 이글의 제목은 "{{ page.title }}" 이고
마지막으로 수정된 시간은 {{ page.last_modified_at }} 이다.

아래는 이미지 관련 테스트

### MD format

![2008 Mini Cooper S](/assets/images/2020-08-20 17.22.07_PS5TGq.png){:class="img-responsive"}

### HTML figure

<figure>
  <img src='{{ "/assets/images/2020-08-20 17.22.07_PS5TGq.png" | relative_url }}' alt='2008 Mini Cooper S' class='img-responsive'>
  <figcaption>2008 Mini Cooper S</figcaption>
</figure>
