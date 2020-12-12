## 블로그 이용방법

### 로컬 설치

이건 나중에....


### 샘플

[데모 사이트](https://lenpaul.github.io/Lagrange/) 에서 샘플 포스트 확인 가능.
`_posts`폴더에서 샘플 포스트 파일 확인.


### 사이트 정보

`_config.yml` 파일을 편집하면 됨. 제목, 설명 등을 커스터마이징하거나 플러그인을 추가하고 싶으면

[the Jekyll documentation site](https://jekyllrb.com/docs/configuration/) 참고.


깃허브에서 사이트를 호스팅중이라면(나의 경우), `_config.yml`을 커밋하여 변경을 주면 사이트를 강제로 rebuild한다. (시간 좀 걸림)

로컬로 호스팅중이라면 `jekyll serve`을 run해야 변경된 부분이 적용된다.


Disqus comments, Google Analytics, 메뉴에서 보일 부분, sns 정보 등은 `_data` 폴더의 `settings.yml` 파일에서 변경할 수 있다.


### 메뉴 카테고리 추가

`menu` 폴더에서 메뉴 페이지를 확인할 수 있다.

`settings.yml` 파일에서 메뉴를 추가할 수 있다.


### 레이아웃

모든 레이아웃은 [YAML front block matter](https://jekyllrb.com/docs/frontmatter/) 양식을 따른다.

YAML front block matter을 포함한 파일은 모두 Jekyll을 통해 생성된다.

말 그대로 페이지 레이아웃... 홈페이지 레이아웃, 포스팅 레이아웃 등을 설정할 수 있음. 예시로


```
---
layout: post
title: "Example Post"
---
```

이건 포스팅 레이아웃. 이 정도만 알고 있으면 될 듯.



### 포스팅

`_posts` 에 `YYYY-MM-DD-name-of-post.md` 형식의 제목을 가진 파일을 추가한다.

YMAL 프론트 블럭(이게 뭐지) 양식은 다음을 따른다.


```
---
layout: 어떤 레이아웃을 쓸지. 보통은 post
title: 포스트 제목
author: 포스트 
categories: 포스트의 장르
tags: [관련된 포스팅과 묶이게 하는 태그]
image: 포스트 대문 커버 사진. `assets` 파일의 `img` 파일에 사진을 추가해야 한다.
---
```


## 기타

### 마크다운

[마크다운 문법](https://guides.github.com/features/mastering-markdown/) 참고해서 포스트 작성.

샘플 포스트 참고해도 됨


### 언어 하이라이트

[fenced code blocks](https://help.github.com/articles/creating-and-highlighting-code-blocks/) 참고해서 포스트 작성.

지원하는 언어는 [여기](https://github.com/jneen/rouge/wiki/List-of-supported-languages-and-lexers) 참고.

관련 옵션은 [Gist](https://en.support.wordpress.com/gist/) 참고.


### 수학 수식
[MathJax](https://www.mathjax.org/) 랑
[LaTeX](http://www.andy-roberts.net/writing/latex/mathematics_1) 참고.


### SNS 아이콘

아이콘은 모두 [Font Awesome](http://fontawesome.io/) 에서 가져온 것.

변경은 `settings.yml` 에서 할 수 있다.

