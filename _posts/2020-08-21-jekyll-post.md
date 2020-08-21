---
title: "Jekyll 설치하고 사용해보기"

categories:
  - Blog
tags:
  - jekyll
  - ruby
last_modified_at: 2020-08-21T12:32:00-0700
---

1.Ruby설치하기

```
brew install ruby
```

그런후 .bashrc 혹은 .zshrc에 환경설정 추가 (설치 끝난후 알려주는 정보에서 설정 추가하는법 알려준다).

2.Jekyll과 bundler 설치하기

```
gem install -n /usr/local/bin jekyll bundler
```

3.Blog만들어보기

```
jekyll new helloBlog

cd helloBlog

bundle exec jekyll serve
```

브라우져로 확인해본다.
