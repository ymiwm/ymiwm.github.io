---
layout: post
title:  "[Issue] Jekyll 블로그 Github 업로드 시 404 Page not found"
date:   2022-01-20 09:00:00 +0900
categories: jekyll blog
---
# 목차
1. [Localhost에서 Github로...!](#1-localhost에서-github로)
2. [404 Page not found](#2-404-page-not-found)
3. [해결법](#3-해결법)
4. [의문점](#4-의문점)
5. [해답](#5-해답)
6. [참조한 자료](#6-참조한-자료)

## 1. Localhost에서 Github로...!
 Github page를 생성하는데에 있어 Localhost에서의 정상실행 확인 후,
{% highlight console %}
git add --all
git commit -m "Blog update"
git push origin master
{% endhighlight %}
위의 과정을 거쳐 Github에 업로드 하였다.

## 2. 404 Page not found
 이후 현재 블로그 주소인 <https://ymiwm.github.io/>{:target="_blank"}로 접속하였으나...  
![404 Error](/assets/images/2022/01/20/404_Error.jpg)

## 3. 해결법
 이와 관련하여 [Stack overflow<sup>1</sup>](https://stackoverflow.com/questions/11577147/how-to-fix-http-404-on-github-pages/45907768#45907768){:target="_blank"}를 통해 찾아낸 방법은 아래와 같았다.
{% highlight console %}
git commit --allow-empty -m "Trigger rebuild"
git push
{% endhighlight %}
뇌피셜로는 빈 상태를 `commit`하여 `git`에 `push`하여 Rebuild를 한 것인데...

## 4. 의문점
 위 과정을 통해 404 Page not found 문제는 해결하였으나 의문점이 많이 남았다.  
이후 의문이 해결된다면 보강할 예정이다.

 1. 이러한 현상이 생기는 이유
 2. 빈 상태를 `commit`, `push`하였을 때 github에서 생기는 변화
 3. 블로그의 정상적인 동작에 필요한 조건

## 5. 해답
 1. WIP
 2. WIP
 3. WIP

## 6. 참조한 자료
*1. How to fix HTTP 404 on Github Pages?*  
<https://stackoverflow.com/questions/11577147/how-to-fix-http-404-on-github-pages/45907768#45907768>{:target="_blank"}