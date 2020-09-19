---
title: "빈도가 제일 높은 단어 찾기"
excert: "Javascript coding interview"

categories:
  - IT
tags:
  - javascript
  - code
last_modified_at: 2020-09-18T19:32:00-0700
---

## Javascript로 빈도수 높은 단어 찾기

얼마전 인터뷰하는데 다음과 같은 질문이 주어졌다. Javascript로 빈도수가 높은 단어 찾아내 화면에 보여주는 프로그램을 만들어야 하는건데, 너무나 오랜만에 이런식의 인터뷰를해서 ~~살짝~~ 아니 많이 당황했었다. 근데 알고보면 쉬운 문제 :)

<script src="https://gist.github.com/codeinlife/6ebc732eb2a1d64ff8d57f78f2a5ef98.js"></script>

이거 궁리하는데 20분이상 걸렸다 어휴 코딩 인터뷰 힘들긴하다. 그래도 다행히 원하는 결과값이 반환되긴했다. 이 질문 말고 다른거 4개 더 있었는데 시간 나는대로 한번 포스트해야겠다.

python으로 했으면 더 쉬웠을것을

<script src="https://gist.github.com/codeinlife/2de9aced9f92538da9ccdea3312ae776.js"></script>

반환된 결과값은

```
{'apple': 2, 'banana': 1, 'grape': 1, 'orange': 1}
```

이정도만 해도 충분했을듯
