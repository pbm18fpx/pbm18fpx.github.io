---
title: jekyll을 이용한 github 블로그 제작기
date: '2020-11-08 19:59:00 +0900'
categories:
  - Blogging
  - 제작
tags:
  - blog
  - github
  - jekyll
published: true
---

## 만들게 된 계기
적지 않은 시간 동안 일을 하면서, 실제로 머리속에 정리된 지식들은 얼마 없다는 것을 깨달았다.
그래서 공부한 것들을 정리 할 가장 적합한 플랫폼이 무엇이 있는지 찾아보게 되었다.

* 네이버 블로그
    * 장점 : 친숙함, 네이버 검색이 잘 됨
    * 단점 : (내가 아무리 열심히 꾸며도) 안예쁨
* 티스토리 블로그
    * 장점 : 네이버 블로그 보다는 꾸밀 수 있는 선택의 폭이 넓음
    * 단점 
        1. 이 글을 작성하는 최근에 다음 사이트 전체가 터져서 티스토리도 터졌었다..
        1. (못 찾은 거 겠지만) 마음에 드는 포맷이 없었다
* github 블로그
    * 장점 : 개발자 다운 포쓰가 느껴진다
    * 단점
        1. 개발자 말곤 잘 모른다
        1. (개발적인 지식이 없으면) 어렵다 -> 모르는 이들에게 짱 멋있어보인다
* Youtube
    * 장점 : 영상이다
    * 단점 : 영상이다
* 생활코딩 튜토리얼
    * 장점 : 이미 관심사가 동일한 사람들이 많이 모여있다
    * 단점 : 내가 .. 튜토리얼을 작성할 만큼 고수인가?

각각 장단점이 있었지만 개발 관련 된 내용들이 정리될 예정이었고,
개발자라면 github 지! 라는 생각에 github 로 블로그를 만드는 방법을 알아보게 되었다.
(그리고 github 블로그들이 보통 매우 멋있었다.)



## 시작하기
### 알아보기
아래 내용은 다 이해하지 못해도 괜찮지만, 이해하면 사용에 도움이 된다.
* git
* [jekyll](http://t-robotics.blogspot.com/2016/04/jekyll.html#.X6vvr2gzaUk)

아래 내용은 문서 작성법에 대한 내용이라 숙지가 필요하다.
* [MarkDown 사용법](https://gist.github.com/ihoneymon/652be052a0727ad59601)



### 설정하기
깃허브 블로그를 만드는 여러가지 방법이 있겠지만 예쁘게 꾸밀 센스가 없는 나와 같은 분들은 이미 만들어져있는 테마를 사용하는 것이 좋을 것이다. 

스탭 별 참고한 포스팅이 있으니 참고하면 좋을 것 같다.

1. [테마 고르기](https://theorydb.github.io/envops/2019/05/02/envops-blog-theme/#jekyll-themes-%EA%B3%A0%EB%A5%B4%EA%B8%B0)
1. [설정](https://theorydb.github.io/envops/2019/05/03/envops-blog-github-pages-jekyll/)
	* 똑같은 테마를 사용한 게 아니라면 작업에 차이가 있을 수 있다
    * jekyll, git에 대한 이해도가 있다면 테마 제공자의 README를 읽으며 작업하면 된다
    * 로컬에서 미리 테스트 할 생각이 없다면, Ruby & Jekyll 를 설치하지 않아도 된다
1. [운영](https://theorydb.github.io/envops/2019/05/04/envops-blog-posting-prose-io/)



### 기타 꿀팁
* [검색](https://theorydb.github.io/envops/2019/05/11/envops-blog-tipue-search/)
* 댓글 설정
	* [Disque](https://17billion.github.io/jekyll/disqus/reply/2017/06/01/jekyll_disqus.html)
    * [github utterances](https://baek.dev/post/4/)
* [통계](https://analytics.google.com/analytics/web/#/)
* [글쓰기](https://theorydb.github.io/envops/2019/05/04/envops-blog-posting-prose-io/)
    

이상 jekyll을 이용해 github blog를 만드는 방법을 알아보았다.
