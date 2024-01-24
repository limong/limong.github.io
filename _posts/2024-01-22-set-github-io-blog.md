---
title: "깃헙 블로그 생성 with Jekyll Pinterest Theme"
metadate: "hide"
categories: [blog, github.io, Jekyll, dev]
image: "/assets/images/post/240122-github-io-blog/main.png"
visit: ""
---

블로그를 만들어야 겠다.

어떻게 만들까 고민하다가 github.io 와 Jekyll 조합을 찾았고 만들어 보았다.

##### github.io repository 생성

- xxxxxx.github.io 이름으로 repository를 생성한다.
  - 나는 limong.github.io로 생성

#### Theme 고르기

- https://jekyll-themes.com/ 에 들어가면 이미 많은 테마들이 있다.
- 가장 마음에 드는 것을 고른 후 해당 repository로 이동하여 소스를 다운로드 받는다.
  - 물론 반대로 fork를 받으면서 repository를 생성하면서 해도 된다.
- 다운로드 받은 소스에서 `.git` 파일을 삭제한다.
  - 해당 파일을 삭제해야 기존 history가 남지 않는다. 안지워도 상관은 없다.

#### Ruby 설지

- Jekyll은 ruby 3.1.3 이상을 추천한다.
  - 낮은 버전을 사용하고 있다면 버전 업데이트를 하자

#### 실행

- Local 환경에서 해당 폴더로 이동하여 아래 명령어를 실행한다.
  - `bundle exec jekyll serve`
- 브라우저를 열고 아래 url을 입력하면 짜잔 뜬다.
  - `http://localhost:4000/template-pintereso-bootstrap-jekyll/`
- 아래처럼 뜨면 성공이다.
  ![/assets/images/post/240122-github-io-blog/main.png](/assets/images/post/240122-github-io-blog/main.png)

#### 커스텀

- 몇가지 마음에 들지 않는 것을 수정해보자.
  - `_config.yaml` 파일을 열면 처음에 아래 코드들이 있다.
  - logo를 변경하고 싶으면 `assets/images` 폴더아래 `logo.png` 이미지를 다른 이미지로 바꾸면 된다.
  - baseUrl를 지우면 `http://localhost:4000/` url 만 입력해도 메인 페이지가 뜬다.
  - 즉, `https://limong.github.io` 만 입력해도 메인 페이지가 뜬다.
  - 아바타 이미지를 바꾸고 싶으면 `assets/images/sal.jpg` 이미지를 본인 이미지로 바꾸면 된다.

```
# Site
name: "limong"
description: ""
logo: "assets/images/logo.png"
favicon: "assets/images/logo.png"
baseurl: ""
avatar: "assets/images/sal.jpg"
disqus: ""
email: "limong.dev@gmail.com"
```
